# Make course materials open and FAIR 

We aim to have all our training materials Open and FAIR. In this context, Open refers to 'publicly accessible' and [FAIR to Findable, Accessible, Interoperable and Reusable](https://www.go-fair.org/fair-principles/). A good place to start would be the paper “[Ten simple rules for making training materials FAIR](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1007854)”. As a second step it is recommended that the trainer uses the [ELIXIR FAIR training handbook](https://elixir-europe-training.github.io/ELIXIR-TrP-FAIR-training-handbook/).  The flow chart below helps to organise the tasks to make your training materials FAIR. 

!!! warning "The flow chart is **not** chronological"
    Note that the ordering in the flowchart is not in an order as you would apply to your training materials. It is rather a way to collect all the activities/resources. However, the numbering is ordered according to the descriptive text, and can loosly be considered as an order of importance, or even a chronological order. 

![](FAIR_training_flowchart.drawio.svg)

## Explanation of the different components

### 1. Metadata

Using metadata is important for making your materials findable and reusable. It is therefore very helpful to check whether the associated metadata is correct, in the right standard and is available.  Metadata can be associated with training materials in many ways. Therefore, depending on the registries/databases you are using, you might have to check your metadata in multiple places. More information in the [FAIR training handbook](https://elixir-europe-training.github.io/ELIXIR-TrP-FAIR-training-handbook/chapters/chapter_04/).

Typically, it depends on the registry or database you are using on which standard is used. So, it depends on the registry you are using what kind of standards you use for your metadata. However, one commonly used standard is the [Bioschemas Training Material standard](https://bioschemas.org/profiles/TrainingMaterial/1.0-RELEASE). This standard is used by amongst others the [TeSS](https://tess.elixir-europe.org/) registry. Another frequently used standard for metadata describing training material is the one used by [zenodo](https://about.zenodo.org/principles/). 

**@SIB:** courses and their materials are automatically annotated based on Bioschemas, and automatically made available in TeSS. If a course is on GitHub and on Glittr.org, an additional Bioschemas annotation is available through Glittr.org, based on the metadata available from GitHub. When a GitHub repository is linked with Zenodo, also a metadata entry is created in Zenodo.

### 2. Attribution

Reuse is a good practice in developing training materials. However, typically it is necessary to give credit to the original authors. For example, if the authors have used a permissive CC-BY license, they should be credited in a way that complies with the license terms.

### 3. License

Without a license, the default copyright laws apply, meaning that no one can use, copy, distribute, or modify the materials. To allow others to use your materials, you need to add a license. For SIB courses, we recommend using the [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/). More information on licenses can be found: 

- [ELIXIR FAIR training handbook](https://elixir-europe-training.github.io/ELIXIR-TrP-FAIR-training-handbook/chapters/chapter_08/#)
- [ELIXIR FAIR material by design course](https://elixir-europe-training.github.io/ELIXIR-TrP-FAIR-Material-By-Design/chapters/chapter_05/#53-licenses)

**@SIB:** we have dedicated [Copyright Guidelines](https://zenodo.org/record/5841604#.ZD8VR-xByX0) for training materials.

### 4. Accessibility 

In order to make materials open for re-use, it is important that potential re-users can easily access them, that they are in a format that can be re-used, and that they are persistently available. (Internal) servers and cloud instances typically do not a very good job in this, because they are often not stable in terms of permissions, availability and persistence. Therefore, it is recommended to use GitHub linked with Zenodo, or, if you are not using GitHub, host materials on Zenodo. If Zenodo is not an option, you can also use other repositories like Figshare, or institutional repositories. 

**@SIB:** we recommend using GitHub linked with Zenodo. As mentioned above, if GitHub is not used, materials can be hosted on Zenodo.

### 5. Versioning system

Using version control like git is a great way to share and collaborate on training materials. You can add your materials directly in the repository, e.g. in GitHub, and let participants interact with the materials through GitHub. It is also possible to host websites with GitHub pages, which might give a nicer interface for the course participants. 

**@SIB:** we recommend using GitHub. You can use the following templates:

- SIB GitHub [repository template](https://github.com/sib-swiss/course_template) (if you don't need a website)
- SIB GitHub [pages template](https://github.com/sib-swiss/course_website_template) (if you want to host a website)

SIB courses are typically hosted within the [SIB GitHub organisation](https://github.com/sib-swiss). Contact a member of the SIB training team to get access to this organisation. If you name the repository, make sure it ends with `-training`. This way, it is clear that it is a training repository.

### 6. Zenodo

Zenodo is a repository that allows you to deposit your materials and assign a DOI to them. It is a great way to make your materials persistent and findable. Zenodo can be used to host training materials, but also to host other materials like software, data, and publications. 

**@SIB:** If you are submitting course material to Zenodo, make sure you add it to the [SIB training community](https://zenodo.org/communities/sib-training/). This way, all SIB training materials are findable in one place.

### 7. Persistent identifier

A persistent identifier (PID) is a long-lasting reference to a document, file, page, or other object. It is used to ensure that the object can always be found, even if the URL changes. The most common PID is the DOI (Digital Object Identifier), which is used for scientific publications. For training materials, the DOI is often used, but there are  PIDs that can be used as well. PIDs are typically assigned if you register your materials in a database or registry.

**@SIB:** For SIB courses, we recommend using Zenodo, which assigns a DOI to your materials. 

### 8. Video materials

Videos of lectures are very valuable materials for both learners and trainers to reuse materials. For sharing of videos you can use YouTube or Vimeo. These platforms are great for sharing and viewing videos, but that they are not for long-term storage. For archiving, you can use Zenodo.

**@SIB:** we use the [SIB YouTube channel](https://www.youtube.com/@SIBTraining). More information [here](../procedure/record_lectures.md). Currently, we do not have a procedure in place for long-term storage. However, they are stored on the SIB servers.

### 9. Glittr.org

Materials that are hosted on GitHub are often hard to find, especially if they are not indexed elsewhere. Glittr.org is a platform that indexes GitHub repositories and makes them findable. It also provides additional metadata based on the metadata available in the GitHub repository.

**@SIB:** All SIB courses on GitHub should be available from Glittr.org. If your course material is missing, submit it at [https://glittr.org/contribute](https://glittr.org/contribute)

### 10. TeSS

TeSS indexes training materials and events from various sources, including GitHub repositories. It is a great platform to make your materials findable. TeSS uses the bioschemas profile that can be automatically scraped from websites. An alternative to using bioschemas is to manually add metadata to TeSS.

**@SIB:** All SIB courses on GitHub should be available from TeSS. They can have multiple entries, one from the bioschemas markup available from the SIB website, and one from Glittr.org. These two entries contain different metadata, so it is recommended to check both entries. 

### 11. Communication

Although now your materials have been made FAIR, it is important to communicate this to the world. You can do this by sharing your materials on social media, in newsletters, or by presenting them at conferences.

**@SIB:** The recommended channel for sharing your training materials is through [the SIB Training linkedin page](https://www.linkedin.com/showcase/sib-swiss-institute-of-bioinformatics-training/).


