---
title: Data Management Plan
layout: page
permalink: /dmp.html
---

# Fairy Tales \- Countless Curses

## Data Management Plan

### Project Description

Our collection is composed of fairy/folk tale illustrations from stories featuring curse narratives throughout the 19th and early 20th centuries, drawing from a variety of different stories, story versions, and illustrators. It may be of interest to those conducting humanities research, or who have a curiosity for different fairy tales, how they have appeared historically, and how curse narratives have reflected societal anxieties of the time. Additionally, because our collection reflects illustration from a wide range of years, it may be of interest to those wanting to see how certain illustrators’ work has changed over time, or how fairy tale illustration as a genre has developed stylistically (as this can vary based on the story version and its location of origin). 

We’re hosting our collection as a website on GitHub, which is a “platform that allows developers to create, store, manage, and share their code.” Specifically, we are using CollectionBuilder Sheets, an open-source template that uses our metadata information to create a cohesive website.  Our website, produced from this software, allows users to view, search, and categorize our items by illustrator, story, medium, featured fairy tale curse, location, and date. 

### Roles and Responsibilities 

**Group Members: Kitty Fields, Maddy Thomas**

We’ve shared responsibilities for managing and entering data throughout our project. We’ve worked together to find individual objects, document and upload them, and coordinate our work on the aesthetic and technical parts of our website.

### Anticipated Data

Our data was collected through various archives, libraries, and museum collections, which we used to both find images and relevant information associated with each object (title, year, illustrator, etc.). While some of the fairy tales we focused on were more well-known, we also used the Aarne-Thompson-Uther index to locate more obscure stories to diversify our collection. 

| Item Description | File Type | Size (MB) | \# of Items | Licenses | Sources |
| :---- | :---- | :---- | :---- | :---- | :---- |
| Illustrations of different fairy tales that contain curse narratives | jpeg/png | 0.4 MB | 28 | Public Domain, No Known Copyright | New York Public Library, Internet Archive, Cleveland Museum of Art, Smithsonian Institute, Wikimedia Commons, University of Maryland Children’s Library, University of Michigan Library, Hathi Trust, University of Florida Digital Collections |

### Documentation and Metadata

We plan on including our data dictionary/appendix as a tab on the homepage of our CollectionBuilder site, which will be helpful for users to see the categories that make up our metadata. Additionally, we have a “Data” tab on our site that allows users to see the metadata associated with each object. In conjunction with our data dictionary, users will be able to see and understand what each category specifically represents, and how it applies to each of our objects.

### Storage and Backup

We’re incorporating several ways of preserving our data while we work on our project. Primarily, our objects and metadata are stored on Github, but we also have a backup folder containing our objects in a shared Google Drive, alongside our metadata sheet. Additionally, copies of our images, as well as a copy of the most recent iteration of our metadata, is stored on our personal computers, which also backup on Microsoft Onedrive. 

### Data Sharing

Our data will be available through our CollectionBuilder website, which contains information about the objects’ titles, creators, years of creation, etc. that may be helpful for reuse. We also link directly to the original repository in which we found each object, allowing for easy access to the source in which the item was found. Additionally, users are able to download our source code through the GitHub repository homepage, which will also allow them to access the images associated with each object. 

### Period of Data Retention

We plan on maintaining our CollectionBuilder site for the duration of this class, as well as keeping our data backups (on personal computers and Google Drive). We will leave the website up after the end of this term, and continue to periodically check for debugging purposes until the start of next term — September 2025\. After this, we don’t plan on actively maintaining or adding to our site, but will leave it up for viewing. 

### Licensing and Ethical Issues

All of the illustrations in our collection are in the public domain, as the majority of them are from before 1929 or have creators who have been dead for more than 70 years. Individually, each of our objects also has a link to a specific rights statement outlining the terms of use for each illustration. 

### Appendix: Data Dictionary

| field | description | example value |
| :---- | :---- | :---- |
| objectid | Unique identifier for each object | coll01 |
| filename | Name of the file, including file type extension. The filename consists of three components to make identification easier: the fairy tale’s title (often abbreviated or as an acronym), the year the object was produced, and the surname of the illustrator. | sw\_1892\_tschautsch.jpg |
| title | Name of the object, either from the original repository or given by the team. | The prince arrives. |
| creator | The name of the illustrator who created the object. | Albert Tschautsch |
| date | The year that the object was created. In some cases, the year is an estimate/approximation. | 1892 |
| medium | The medium that the object was created in. If no information is available about the object’s medium, the field is left blank. | Wood Engraving  |
| description | A detailed description of the object, as it is illustrated.  | The prince arrives to see Snow White asleep in her coffin, surrounded by the seven dwarves. |
| featuredcurse | A broad category for the type of curse featured in the fairy tale. Possible values include: sleeping curse; animal transformation; voice loss, cursed to die; mirror curse altering personality; dancing curse; unspecified curse as punishment. | sleeping curse |
| subject | The title of the fairy tale associated with the illustration.  | Snow White |
| location | The fairy tale’s country of origin. | Germany |
| latitude | The geographic coordinate detailing the north-south position of the object’s country of origin. | 50.890781 |
| longitude | The geographic coordinate detailing the east-west position of the object’s country of origin. | 10.448669 |
| source | A link to the original repository where the object was found. | [https://digitalcollections.nypl.org/items/69442d4b-78ff-76b8-e040-e00a18065389](https://digitalcollections.nypl.org/items/69442d4b-78ff-76b8-e040-e00a18065389) |
| type | A further specification of our objects, defined as an image, stillimage, movingimage, text, etc. | Image;stillimage |
| format | The object’s file type. | image/jpeg |
| rights | The rights of the specific object. | No known Copyright |
| rightsstatement | A link to the rights statement defining how the object can be shared with the public. | [https://rightsstatements.org/page/NKC/1.0/?language=en](https://rightsstatements.org/page/NKC/1.0/?language=en) |
