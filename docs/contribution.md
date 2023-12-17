# Contribution Guideline

---

This document describes the contribution guideline for event organizers who want to add their event's exam questions and problems to this repository. Please read this document carefully before contributing to this repository.

## Getting Started

To contribute to this repository, please follow these steps:

1. **Fork** this repository.
2. **Clone** the repository to your local machine.
3. **Create a new folder** with the name of the year of your event.
4. **Add your exam questions and problems** to the folder you just created.
   > For file structure, please follow the structure of the existing folders. or you may refer to this [section](#repositorys-folder-structure) for more information.
5. **Commit and push** your changes to your forked repository.
   > Please follow the [commit message convention](convention.md) when writing your commit message.
6. **Create a pull request** to this repository.
   > Pull request guideline will be added soon.

## Folder's Contents

Each folder in this repository should contain the following contents:

#### Exam Questions and Problems

The exam questions and problems is recommended to be written in Markdown format, so that participants can read them directly on GitHub. The file name should be `detail.md`.

Alternatively, pdf files can also be added to the folder if Markdown file is not available. Similarly, the file should be named as `detail.pdf`; however, Markdown file is preferred over pdf file as it can viewed directly on GitHub and does not required viewer to download the file.

#### Test Cases

**There must be no test cases provided in this repository**. In case some of test are to be reused, adding test cases will damage the integrity of the exam questions and problems. Thus, test cases are prohibited in this repository.

#### Solutions

Similar to test cases, **No solutions is prohibited in this repository**. The purpose of this repository is to provide a reference to the exam questions and problems, so that participants can prepare themselves for the event. Thus, providing solutions will defeat the purpose of this repository.

### Test Assets

Other files that might be needed for the exam questions and problems, such as images, videos, etc.

All of those files should be placed in the same folder as the exam questions and problems. Create a folder within that exam questions and problems folder called `assets` and place all of those files in that folder.

## Repository's Folder Structure

This document describes the folder structure of this repository for event organizers or contributor who want to add their event's exam questions and problems to this repository.

The folder structure of this repository should be as follows:


```txt
root
├── <Year>
│   ├── Round1
│   │   ├── <Problem 1 Name>
│   │   │   ├── detail.md
│   │   │   ├── assets (optional)
│   │   │       ├── <Asset Files>
│   │   │           ...
│   │   ├── <Problem 2 Name>
│   │       ├── detail.md
│   │       ├── assets (optional)
│   │           ├── <Asset Files>
│   │               ...
│   ├── Round2
│   │   ├── <Problem 1 Name>
│   │   │   ├── detail.md
│   │   │   ├── assets (optional)
│   │   │       ├── <Asset Files>
│   │   │           ...
│   │   ├── <Problem 2 Name>
│   │        ...
│   ├── Round3 
|   │   ...
(and so on depending on how many rounds your event has)
```
