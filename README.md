# vaibhav-curriculum

Pre-reads and lecture scripts for the IITREICT DAAI batches, in the team's standard structure.

## Repository layout

```
vaibhav-curriculum/
├── README.md
├── templates/
│   ├── pre-read-template.md
│   └── lecture-script-template.md
├── <batch-id>/                       # same ID as the INI sheet
│   ├── module-01-<topic>/
│   │   ├── lecture-01-<topic>/
│   │   │   ├── pre-read.md
│   │   │   ├── lecture-script.md
│   │   │   ├── data/                 # only when the script needs datasets
│   │   │   └── images/               # only when the script shows charts
│   │   └── ...
│   └── ...
└── ...
```

## Batches

| Batch id | Sessions in this repo |
|---|---|
| `IITREICT-DAAI-EN-II-2607` | Lecture 10, Joins II (pre-read). Lecture 11, Subqueries (pre-read and lecture script). |

## Naming rules

- Folder names use lowercase letters, digits and hyphens only. Batch folders keep the INI sheet ID as written.
- Modules and lectures are numbered with two digits: `module-01-…`, `lecture-06-…`.
- Lecture numbers follow the batch's academic session order. Masterclasses are not counted.
- Each lecture folder uses the same two file names: `pre-read.md` and `lecture-script.md`.
- A session's datasets go in `data/` and its charts in `images/`. Scripts link to them with relative paths.

## Templates

`templates/` holds the team pre-read and lecture-script templates, unchanged (lecture script format v2). Every new file starts from them.

## SQL sessions

Each SQL lecture script ships its loader in `data/<name>.sql`. Open the file in MySQL Workbench and run it once before the class. The script's outputs come from MySQL 8.
