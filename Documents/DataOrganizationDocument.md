#Data Organization Document
#####Team Rigmarole: Giorgio Liggio, Alessio Quercia, Andrea Salamone

##Document Information
* | *
------------ | -------------
**Purpose** | To keep an organization over the data used for the project
**Creation date** | 01/11/2017
**Current owner** | Alessio Quercia
**Last modification** | 23/11/2017

##**Revision History**

Who | When | What | Version
------------    | :-------------: | ------------ | :-------------:
Alessio Quercia | 01/11/2017 | Created this document | 0.1
Alessio Quercia | 07/11/2017 | First rough version of the document| 1.0
Alessio Quercia | 16/11/2017 | Changed document structure and content | 1.1
Alessio Quercia | 17/11/2017 | Modified the Directory Structure section and added content related to File Naming Convention | 1.2
Alessio Quercia | 23/11/2017 | Changed document structure and modified the Directory Structure section| 1.2.1
Alessio Quercia | 24/11/2017 | Added the directory structure image and its description into the Directory Structure section| 1.3

##**Contacts**

Team Member | Email
------------ | -------------
Giorgio Liggio | giorgiomaria.liggio@studenti.unimi.it
Alessio Quercia | alessio.quercia@studenti.unimi.it
Andrea Salamone | andrea.salamone1@studenti.unimi.it

##Software List
In the following sections are listed the softwares (together with their versions) we will use during the project to edit assets, to develop and organize the project, and the environments used to develop the project. The software list is still work in progress, indeed we might add or remove softwares from the list, depending on what we will need. For the moment, we listed the essential softwares we assumed we are going to need.
###Asset Editing Software
In this section are listed the softwares we will use to edit assets (such as textures, sprites, images and 3D models):
- _Gimp 2.8_, to make and edit the textures, sprites and images.
- _Sketchup Make 2017_, to make and edit 3D models.
- _lender 2.79_, to export 3D models.

###Development Software
In this section are listed the softwares we will use to develop the project:
- _Neverwinter Nights 2 Toolset 1.0_, to prepare a playable level prototype.
- _GIT_, to keep trace of our documents versions and also to store our main master copy of the project.

###Organization Software
In this section are listed the softwares we will use to develop the project:
- _Office 2016_, to format project documents.
- _Google Documents_, to format project documents.
- _Markdown_, to write project documents and keep their versioning on GitHub.

###Environments
We are going to develop the project on Windows 10 Home system (version 1709). Every team member has already his own copy of the system on his personal computer.

##Data Types and Format
In the following sections are listed the different file types, format and extensions of the project data. The list is still work in progress, indeed we might add or remove formats from the list, depending on what we will need. For the moment, we listed the essential data types, format and extensions, based on what we needed.

###Texts
In this section are listed the format and the extensions of the texts and documents of the project:
- _DOC_ (.doc) for the documents.
- _PDF_ (.pdf) for the refined documents.
- _Markdown_ (.md) to keep the documents versioning on GitHub.

###Pictures
In this section are listed the format and the extensions of the pictures of the project:
- _JPEG_ (.jpg)
- _PNG_ (.png)

###Videos
In this section are listed the format and the extensions of the videos of the project:
- _Matroska_ (.mkv)
- _AVI_ (.avi)
- _MP4_ (.mp4)

###Audios
In this section are listed the format and the extensions of the audios of the project:
- _MP3_ (.mp3)
- _WAV_ (.wav)

###3D Models
In this section are listed the format and the extensions of the 3D models of the project:
- _COLLADA_ (.dae)
- _OBJ_ (.obj)

##Data Storage and Access
Our data is stored in the following GitHub private repository: [GameAndLevelDesign](https://github.com/AlessioQuercia/GameAndLevelDesign). Only the team members are able to access and manage data inside this repository because it is private. We decided to use GIT to keep trace of our changes to the documents all over the project duration. Thanks to GIT we have a working versioning system for our documents and also a way to store and keep safe our data from incorrect changes. In fact, we keep our master copy of the project into GitHub and we work in our local branches of the master. After we have finished some work on our local copies, we make a push request and then we merge the changes into the master copy together. In this way, a master copy updated to the last working version is always stored into GitHub and three local branches (one for each member) are used for our local work.
###Backup
If a member accidentally loses his local copy, he might clone the master copy and restart from the last working version. Besides, to avoid losing the master copy, we keep last N working versions into the following Google Drive private directory as backup: [GLD](https://drive.google.com/drive/folders/1vC3n0fM9adhMxMBctSkhzV4wbIy7tjTz)*. For safety, we also keep these last N working versions into an external hard drive.
The list below represents a summing up of the project and his backups locations:
- Master copy is held inside the following GitHub private repository: [GameAndLevelDesign](https://github.com/AlessioQuercia/GameAndLevelDesign).
- Last N working versions of the master are stored in the following locations:
 - A Google Drive private directory ([GLD](https://drive.google.com/drive/folders/1vC3n0fM9adhMxMBctSkhzV4wbIy7tjTz)).
 - An external hard drive.
- Every team member has his own local copy of the last working version of the master on his personal computer.
- Every team member works on a different local branch of the last working version of the master (three branches, one for each member).

*Refined documents are also stored into this directory.

###Directory Structure
In this section is described the directory structure of the project, which is the same as the repository in which the project is stored ([GameAndLevelDesign](https://github.com/AlessioQuercia/GameAndLevelDesign)). The structure is shown in the image below:

![alt text][structure]
[structure]: http://i65.tinypic.com/2cqff9l.png


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
- _Texts_, containing the game related texts. This directory is divided into two different directories:
 - _Dialogues_, containing the dialogues' texts.
 - _GameplayTexts_, containing the texts related to the gameplay itself.

##File Naming Convention

To keep an organization over the files, their names are chosen in a consistent and descriptive way, so that it’s easier to store or find a file and to understand its content by reading its name. A file naming convention also helps us to distinguish files from each others and to keep a chronological order between them, according to their creation date. Indeed we adopted the following file naming convention for our project’s files:
- Project name: GLD (standing for Game and Level Design project).
- Creation date in the format YYYYMMDD, to keep files in chronological order.
- Location: the file parent directory (abbreviated).
- Type of data: the file type, base on his parent directory.
- Conditions: filename and, eventually, attributes. The conditions have the camel case format.
- Version number of the file in the format (v#)
- File extension: (.extension)

Each item of this list, except for the file extension, is separated from the others by an underscore (“_”). So, a general file should have the following name format:

ProjectName_CreationDate_Location_Type_Conditions_Version.Extension

For example, this document is stored as:

GLD_20170111_Docs_Ref_DataManagementDocument_v1.doc



