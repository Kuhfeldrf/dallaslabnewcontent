# Dallas Lab Website Content Repository

## Overview

This repository contains the content for the Dallas Lab website at Oregon State University. The markdown files in this repository are **content updates only** and are not responsible for website formatting or styling. They serve as the source material for web developers to implement into the actual website structure and an edible format for the Dallas lab team to make changes to.

## Repository Structure

```
├── pages/
│   ├── main_website_content.md     # Main page content
│   └── [service-pages].md          # Secondary service pages (Q&A format)
├── images_for_site/                # Image assets for the website
├── catagorized_publications.csv    # Categorized publications with keywords
└── README.md                       # This file
```

## Content Organization

### Main Page (`main_website_content.md`)
- Located in the `pages/` directory
The main page file contains summarized content organized into three main sections:
1. **Research Section** - Overview of current research areas
2. **Services Section** - Laboratory services and capabilities  
3. **About Us Section** - Information about the lab and team

### Secondary Pages (Service Pages)
- Located in the `pages/` directory
- Formatted as Q&A (Question & Answer) content
- Each page focuses on specific services or research areas
- Linked from the main page content

### Images
- Stored in the `images_for_site/` folder
- Referenced within markdown files using relative paths
- **Important**: Only the main page has images arranged in the correct order
- Secondary pages may need image placement review during implementation
- Please add additional images as the current selection is weak

### Publications Database
- **File**: `catagorized_publications.csv`
- **Purpose**: Spreadsheet containing recent lab publications grouped by associated keywords
- **Usage**: Keywords can be used to dynamically link publications to relevant services and research topics
- **Implementation**: Web developer can use this data to create publication sections on relevant pages

## For Web Developers

### Implementation Instructions

1. **Content vs. Formatting**: The markdown files contain only content. You are responsible for:
   - Implementing the website structure and layout, please use your best discretion

2. **Style Reference**: Use the demo website as a style guide:
   - Demo URL: https://kuhfeldrf.github.io/dallasdemo/dallas-lab-website.html
   - **Note**: The demo content is outdated; use only for visual/style reference

3. **Content Integration**:
   - Parse the markdown files to extract content
   - Maintain the three-section structure of the main page (Research, Services, About Us)
   - Implement Q&A formatting for secondary pages

4. **Image Implementation**:
   - Images are referenced with relative paths in markdown
   - Only main page images are properly ordered
   - Verify image placement and order for secondary pages
   - Ensure all images from `images_for_site/` are accessible
   - Please use your discretion to improve the images for the website

5. **Publications Integration**:
   - Use `catagorized_publications.csv` to  associated publication to key words
   - the key words and topics in `catagorized_publications.csv` are the pulled from the reaserch and services in the main page

6. **Navigation**: 
   - Use `main_website_content.md` as the navigation reference
   - Create links to secondary pages as indicated in the main content
   - Ensure responsive navigation for mobile devices

### Future Development Notes

- **Research Section Expansion**: The goal is to develop expanded content and create secondary pages for each key research area. This is not yet completed, so plan your site structure to accommodate future research detail pages.

- **Refferals**: The goal is to develop a refferals or testiminoal section as seen in the demo page but this content has yet to be developed.

## For Dave, Jen, Clay, Bumjin, other Dallas Lab members

### Editing Content

#### Quick Access
- **Direct Editing**: Access and edit files through SharePoint: https://oregonstateuniversity.sharepoint.com/:f:/s/DallasLab/Ehm60pWQeNdPqR0YwhUb9oUB2I6sehougStODLtxBcANKA

#### File Editing Options

##### Viewing Content
- **Through GitHub** (Recommended for viewing):
   - Navigate to the file you want to edit
   - Click the pencil icon to edit
   - Best for seeing formatted preview

##### Editing Content
- **Through SharePoint** (Recommended for editing):
   - Use the SharePoint link above
   - Files can be edited and saved directly
   - Changes sync with the GitHub repository

- **Local Editing**:
   - I recomed Notepad as a local editor of markdown files
   - Files can be edited in any text editor (Notepad, TextEdit, etc.)
   - For best results, use a markdown-aware editor

#### Content Guidelines

##### Main Page Content
- **Research Section**: Keep descriptions concise but informative
- **Services Section**: Focus on what the lab offers to external collaborators
- **About Us**: Maintain professional but approachable tone

##### Secondary Pages (Q&A Format)
- **Questions**: Clear, specific questions potential clients might ask
- **Answers**: Comprehensive but accessible explanations
- **Technical Details**: Include relevant technical information while remaining readable

#### Image Management

- **Adding Images**: 
  - Place new images in the `images_for_site/` folder
  - Reference them in markdown as: `![Alt text](../images_for_site/filename.jpg)`
  - Use descriptive filenames following current format

- **Image Order**: 
  - Main page images are correctly ordered
  - Secondary pages images should just be added to bottom of the page



**Last Updated**: [07/16/25]
**Repository**: https://github.com/Kuhfeldrf/dallaslabnewcontent