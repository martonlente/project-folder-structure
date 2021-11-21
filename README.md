# Project folder structure
Project folder structure is a cross-platform, and cross-software folder structure, and file naming convention for design, and web development projects, designed to help you in efficient file management. It gives a solid base for directory organization, that's open for extension, without introducing any operation system, or software assumptions. :file_folder:

Project folder structure is under construction. :construction:

## Usage
Use this folder structure layout.

```
.
├── backup
├── creative
│   ├── design
│   ├── photo
│   └── pub
├── dev
│   └── app
│       ├── css
│       ├── data
│       ├── fonts
│       ├── img
│       ├── include
│       ├── js
│       └── lib
├── doc
├── img
├── in
├── out
└── viz
    ├── 3d
    └── render
```

### Backup
Store backup files in the `backup` folder, in the according sub-folder. Organize sub-folders by date, for example store files backed up on 1st January 2021 in sub-folder `210101`.

### Creative
Store creative files in the `creative` folder, in the according sub-folder.

#### Design
Store vector design files in the `design` folder, for example logo, UI, and other design files. Common filetypes you can put here are for example `afdesign`, `ai`, `svg`, etc.

#### Photo
Store image editor files in the `photo` folder, for example compositor, post-production, and other photo editor files. Common filetypes you can put here are for example `afphoto`, `psd`, `xcf`, etc.

#### Pub
Store desktop publishing files in the `pub` folder, for example digital, and print publishing files. Common filetypes you can put here are for example `afpub`, `indd`, `sla`, etc.

### Dev
Store web development files in the `dev` folder, in the according application sub-folder.

#### App
Store application in the `app` sub-folder. You can have multiple application sub-folders, if needed. Name application subfolders to match their Git repositories', for example `project-folder-structure` for this repository. Create VirtualHosts for each of these folders.

### Doc
Store document files in the `doc` folder, for example presentation, spreadsheet, word processor, and other text document files. Common filetypes you can put here are for example `docx`, `pptx`, `xlsx`, etc.

### Img
Store image files in the `img` folder.

### In
Store incoming files in the `in` folder, in the according sub-folder. Organize sub-folders by date, for example store files received on 1st January 2021 in sub-folder `210101`. Don't change files, or don't create new files in these folders.

### Out
Store outgoing files in the `out` folder, in the according sub-folder. Organize sub-folders by date, for example store files sent on 1st January 2021 in sub-folder `210101`.

### Viz
Store visualization files in the `viz` folder, in the according sub-folder.

#### 3d
Store 3d files in the `3d` folder, for example 3d model, material, and other drawing files. Common filetypes you can put here are for example `blend`, `c4d`, `max`, etc.

#### Render
Store rendered files in the `render` folder, for example animation, image, and other output files.

Create sub-folders, if needed, to group related files.

## Contributing
Pull requests are not yet welcome. For support requests, please open an issue first to discuss what you would like to change.

## License
[MIT](https://github.com/martonlente/project-folder-structure/blob/main/LICENSE)
