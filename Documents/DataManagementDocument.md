# Rigmarole DevTeam





# *Unnamed Project*

# Data Management Document





**About this document**

| Property      | Description                              |
| ------------- | ---------------------------------------- |
| Purpose       | Set workflow guidelines; define data types & specs; define files management rules. |
| Creation date | 01/11/2017                               |
| Current owner | Alessio Quercia                          |
| Last edited   | 21/12/2017                               |



**Rigmarole Team**

| Team Member     | Email                                 |
| --------------- | ------------------------------------- |
| Giorgio Liggio  | giorgiomaria.liggio@studenti.unimi.it |
| Alessio Quercia | alessio.quercia@studenti.unimi.it     |
| Andrea Salamone | andrea.salamone1@studenti.unimi.it    |








<sub><sub>This document (including any attachments) may contain confidential, proprietary, privileged and/or private information. The information is intended to be</sub></sub><br/><sub><sup>for the use of the individuals or entity designated above. Any disclosure, reproduction, distribution or other use of this document or any attachment by an</sub></sup><br/><sup><sup>individual or entity other than the intended recipients is prohibited.</sup></sup>

<div style="page-break-after: always;"></div>

# Revision history

| Who             |    When    | What                                     | Version |
| --------------- | :--------: | ---------------------------------------- | :-----: |
| Alessio Quercia | 01/11/2017 | Created this document.                   |   0.1   |
| Alessio Quercia | 07/11/2017 | First rough version of the document.     |   1.0   |
| Alessio Quercia | 16/11/2017 | Changed document structure and content.  |   1.1   |
| Alessio Quercia | 17/11/2017 | Modified the Directory Structure section and added content related to File Naming Convention. |   1.2   |
| Alessio Quercia | 23/11/2017 | Changed document structure and modified the Directory Structure section. |  1.2.1  |
| Alessio Quercia | 24/11/2017 | Added the directory structure image and its description into the Directory Structure section. Modified the File Naming Convention. |   1.3   |
| Alessio Quercia | 25/11/2017 | Second version of the document.          |   2.0   |
| Giorgio Liggio  | 21/12/2017 | Refactored document, improved formatting, fixed minor inconsistencies, added disclaimer, added ToC. |  2.0.1  |
| Giorgio Liggio  | 24/12/2017 | Expanded content, improved formatting, fixed grammar, fixed major inconsistencies, removed ToC and added Index. |   2.1   |

<div style="page-break-after: always;"></div>

# Index

[ handmade index to be done ]

<div style="page-break-after: always;"></div>

# 1. Software list
The following sections list all software tools the development team agreed upon and will be using during the project development, regarding: resources (*assets*) editing, workflow management, project planning, and work environment specifications. This section is subject to changes depending on project's requirements or development needs.



## 1.1. Assets editing software
The following software is used to create, edit, import/export assets resources (such as: textures, audio files, 3D models):

- *GIMP* (v.2.8), to create and edit sprites, textures, and other raster graphics;
- *draw.io* (v.7.8.8), to create and edit vector-based diagrams and blueprints;
- *Sketchup Make* (2017 ed.), to create and edit 3D models;
- *Blender* (v.2.79), to export 3D models.



## 1.2. Development software
The following software is used to create and edit project software files and documentation, and manage project versioning:

- *Markdown* (v.x.x), *Typora* (v.0.9.41 (beta) ), to write and export markdown-based documentation files;
- *Microsoft Office* (2016 ed.), to format and export documentation files;
- *Neverwinter Nights 2 Toolset* (v.1.0), to create and test a playable level prototype;
- *GitHub Desktop* (v.1.0.10+), to interface with online project repository and manage version control.



## 1.3. Organization software
The following software is used as task support and coordination by the development team:
- *Telegram Messenger* (any version), *Discord* (any version), for team communication and coordination;
- *Google Drive*, to share temporary files among the team members, and keep track of to-do tasks and project deadlines.



## 1.4. Environments
Development environment for every team members is their personal laptop running Windows 10 Home (version 1709) and Windows 10 Professional (version 1607). No hard constrains are set for environment development, apart from maintaining the same OS major version for optimal performances as of software adopted.

<div style="page-break-after: always;"></div>

# 2. Data types and format (FROM HERE ON)
In the following sections are listed the different file types, format and extensions of the project data. The list is still work in progress, indeed we might add or remove formats from the list, depending on what we will need. For the moment, we listed the essential data types, format and extensions, based on what we needed.

## 2.1. Texts
In this section are listed the format and the extensions of the texts and documents of the project:
- _DOC_ (.doc) for the documents.
- _PDF_ (.pdf) for the refined documents.
- _Markdown_ (.md) to keep the documents versioning on GitHub.

## 2.2. Pictures
In this section are listed the format and the extensions of the pictures of the project:
- _JPEG_ (.jpg)
- _PNG_ (.png)

## 2.3. Videos
In this section are listed the format and the extensions of the videos of the project:
- _Matroska_ (.mkv)
- _AVI_ (.avi)
- _MP4_ (.mp4)

## 2.4. Audios
In this section are listed the format and the extensions of the audios of the project:
- _MP3_ (.mp3)
- _WAV_ (.wav)

## 2.5. 3D models
In this section are listed the format and the extensions of the 3D models of the project:
- _COLLADA_ (.dae)
- _OBJ_ (.obj)

<div style="page-break-after: always;"></div>

# 3. Data storage and access
Our data is stored in the following GitHub private repository: [GameAndLevelDesign](https://github.com/AlessioQuercia/GameAndLevelDesign). Only the team members are able to access and manage data inside this repository because it is private. We decided to use GIT to keep trace of our changes to the documents all over the project duration. Thanks to GIT we have a working versioning system for our documents and also a way to store and keep safe our data from incorrect changes. In fact, we keep our master copy of the project into GitHub and we work in our local branches of the master. After we have finished some work on our local copies, we make a push request and then we merge the changes into the master copy together. In this way, a master copy updated to the last working version is always stored into GitHub and three local branches (one for each member) are used for our local work.

## 3.1. Backup
Master copy is held inside the following GitHub private repository: [GameAndLevelDesign](https://github.com/AlessioQuercia/GameAndLevelDesign).
If a member accidentally loses his local copy, he might clone the master copy and restart from the last working version. Besides, to avoid losing the master copy, we keep last N working versions into the following Google Drive private directory as backup: [GLD](https://drive.google.com/drive/folders/1vC3n0fM9adhMxMBctSkhzV4wbIy7tjTz)*. For safety, we also keep these last N working versions into an external hard drive.

*Refined documents are also stored into this directory.

<div style="page-break-after: always;"></div>

# 4. Directory structure
In this section is described the directory structure of the project, which is the same as the repository in which the project is stored ([GameAndLevelDesign](https://github.com/AlessioQuercia/GameAndLevelDesign)). The structure is shown in the image below:

![Directory structure](img/DMD_DirectoryStructure.png?raw=true)

Each directory contains specific data, according to its name. For this reason, it should be easy to know where to store a file, once it is created, or to retrieve an existing file. For the moment the directory structure is still work in progress, this means we may add or remove directory/files to create a better structure.
The main directory contains two different directories: _Assets_ and _Documents_. This last one contains the game related documents, such as the Game Story Document or this document (Data Organization Document). The _Assets_ directory contains all the game assets and it's divided into other five directories:
- _Textures_, containing the game textures. This directory is divided into three directories:
 - _Objects_, containing the textures related to the game Objects.
 - _Actors_, containing the textures related to the game Actors.
 - _HUD_, containing the textures related to the game HUD.
- 3D Models, containing the game models. This directory is divided into two directories:
 - _Objects_, containing the objects' models.
 - _Actors_, containing the actors' models.
- _Videos_, containing the game videos.
- _Audios_, containing the game audios. This directory is divided into three directories:
 - _Music_, containing the game music.
 - _Dialogues_, containing the game dialogues.
 - _SFX_, containing the sound effects. This directory is divided into two different directories:
   - _Environment_, containing enviromental sound effects.
   - _Actors_, containing actors related sound effects.
- _Lang_, containing the game related texts. This directory is divided into two different directories:
 - _Dialogues_, containing the dialogues' texts.
 - _GameplayTexts_, containing the texts related to the gameplay itself.
- _Concepts_, containing the concept arts related to the game (such as images for the documents).

<div style="page-break-after: always;"></div>

# 5. File naming convention

To keep an organization over the files, their names have to be chosen in a consistent and descriptive way, so that it’s easier to store or find a file and to understand its content by reading its name. For this reason we adopted the PascalCase practice and the following file naming convention for the files in our project:
- For the documents:
 - _(DocumentName)_ (e.g. "DataManagementDocument.md")
- For the images related to the documents:
 - _(DocumentName)_\__(ImageName)_* (e.g. "DMD_DirectoryStructure.png")
- For the assets:
 - _(AssetTypeAbbreviation)(Category)[1-N]\(Name)_\__(Attribute)[0-N]_ (e.g. "TexPropsChest_Small.png")

*In case of a long file name, an appropriate abbreviation of the _DocumentName_ will be used.

The asset types (and their respective abbreviations) are the following ones:
- Textures (Tex)
- 3D Models (3dm)
- Videos (Vid)
- Audios (Aud)
- Lang (Lang)
- Concepts (Conc)

The category identifies what the file is related to and at least one is needed.
Attributes are optional.