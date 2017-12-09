# Data Organization Document
##### Team Rigmarole: Giorgio Liggio, Alessio Quercia, Andrea Salamone

## Document Information
 - | Information
------------ | -------------
**Purpose** | To keep an organization over the data used for the project
**Creation date** | 01/11/2017
**Current owner** | Alessio Quercia
**Last modification** | 25/11/2017

## **Revision History**

Who | When | What | Version
------------    | :-------------: | ------------ | :-------------:
Alessio Quercia | 01/11/2017 | Created this document | 0.1
Alessio Quercia | 07/11/2017 | First rough version of the document| 1.0
Alessio Quercia | 16/11/2017 | Changed document structure and content | 1.1
Alessio Quercia | 17/11/2017 | Modified the Directory Structure section and added content related to File Naming Convention | 1.2
Alessio Quercia | 23/11/2017 | Changed document structure and modified the Directory Structure section| 1.2.1
Rigmarole Team | 24/11/2017 | Added the directory structure image and its description into the Directory Structure section. Modified the File Naming Convention| 1.3
Alessio Quercia | 25/11/2017 | Second version of the document| 2.0

## **Contacts**

Team Member | Email
------------ | -------------
Giorgio Liggio | giorgiomaria.liggio@studenti.unimi.it
Alessio Quercia | alessio.quercia@studenti.unimi.it
Andrea Salamone | andrea.salamone1@studenti.unimi.it

## Software List
In the following sections are listed the softwares (together with their versions) we will use during the project to edit assets, to develop and organize the project, and the environments used to develop the project. The software list is still work in progress, indeed we might add or remove softwares from the list, depending on what we will need. For the moment, we listed the essential softwares we assumed we are going to need.
### Asset Editing Software
In this section are listed the softwares we will use to edit assets (such as textures, sprites, images and 3D models):
- _Gimp 2.8_, to make and edit the textures, sprites and images.
- _Sketchup Make 2017_, to make and edit 3D models.
- _Blender 2.79_, to export 3D models.

### Development Software
In this section are listed the softwares we will use to develop the project:
- _Neverwinter Nights 2 Toolset 1.0_, to prepare a playable level prototype.
- _GIT_, to keep trace of our documents versions and also to store our main master copy of the project.

### Organization Software
In this section are listed the softwares we will use to develop the project:
- _Office 2016_, to format project documents.
- _Google Documents_, to format project documents.
- _Markdown_, to write project documents and keep their versioning on GitHub.

### Environments
We are going to develop the project on Windows 10 Home system (version 1709). Every team member has already his own copy of the system on his personal computer.

## Data Types and Format
In the following sections are listed the different file types, format and extensions of the project data. The list is still work in progress, indeed we might add or remove formats from the list, depending on what we will need. For the moment, we listed the essential data types, format and extensions, based on what we needed.

### Texts
In this section are listed the format and the extensions of the texts and documents of the project:
- _DOC_ (.doc) for the documents.
- _PDF_ (.pdf) for the refined documents.
- _Markdown_ (.md) to keep the documents versioning on GitHub.

### Pictures
In this section are listed the format and the extensions of the pictures of the project:
- _JPEG_ (.jpg)
- _PNG_ (.png)

### Videos
In this section are listed the format and the extensions of the videos of the project:
- _Matroska_ (.mkv)
- _AVI_ (.avi)
- _MP4_ (.mp4)

### Audios
In this section are listed the format and the extensions of the audios of the project:
- _MP3_ (.mp3)
- _WAV_ (.wav)

### 3D Models
In this section are listed the format and the extensions of the 3D models of the project:
- _COLLADA_ (.dae)
- _OBJ_ (.obj)

## Data Storage and Access
Our data is stored in the following GitHub private repository: [GameAndLevelDesign](https://github.com/AlessioQuercia/GameAndLevelDesign). Only the team members are able to access and manage data inside this repository because it is private. We decided to use GIT to keep trace of our changes to the documents all over the project duration. Thanks to GIT we have a working versioning system for our documents and also a way to store and keep safe our data from incorrect changes. In fact, we keep our master copy of the project into GitHub and we work in our local branches of the master. After we have finished some work on our local copies, we make a push request and then we merge the changes into the master copy together. In this way, a master copy updated to the last working version is always stored into GitHub and three local branches (one for each member) are used for our local work.

### Backup
Master copy is held inside the following GitHub private repository: [GameAndLevelDesign](https://github.com/AlessioQuercia/GameAndLevelDesign).
If a member accidentally loses his local copy, he might clone the master copy and restart from the last working version. Besides, to avoid losing the master copy, we keep last N working versions into the following Google Drive private directory as backup: [GLD](https://drive.google.com/drive/folders/1vC3n0fM9adhMxMBctSkhzV4wbIy7tjTz)*. For safety, we also keep these last N working versions into an external hard drive.

*Refined documents are also stored into this directory.

### Directory Structure
In this section is described the directory structure of the project, which is the same as the repository in which the project is stored ([GameAndLevelDesign](https://github.com/AlessioQuercia/GameAndLevelDesign)). The structure is shown in the image below:

![alt text][structure]
[structure]: DirectoryStructure.png?raw=true


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

## File Naming Convention

To keep an organization over the files, their names have to be chosen in a consistent and descriptive way, so that it’s easier to store or find a file and to understand its content by reading its name. For this reason we adopted the PascalCase practice and the following file naming convention for the files in our project:
- For the documents:
 -  _(DocumentName)_ (e.g. "DataOrganizationDocument.md")
- For the images related to the documents:
 - _(DocumentName)_\__(ImageName)_* (e.g. "DOD_DirectoryStructure.png")
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
