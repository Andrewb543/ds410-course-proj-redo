# ds410-course-proj-redo

I have example code up in examples/data_proc_example.ipynb

you don't need to run the get data script, i already have the necessary files downloaded. we need to modify the script if we want to get the data from a different month though

look at the jupyter notebook in the playground folder for my work in extracting the plaintext WET file in parallel

also request at least 16 GB of ram on ROAR when you're trying to run the notebook

## REPO STRUCTURE
```markdown
ds410-course-proj-redo
├── data
│   ├── warc.paths        : Paths to Common Crawl WARC files
│   ├── wat.paths         : Paths to Common Crawl WAT files
│   └── wet.paths         : Paths to Common Crawl WET files
├── dataproc
│   └── dataproctools.py  : Utilities for downloading/processing WET files into RDDs
├── examples
│   └── data_proc_example.ipynb : Demo of using dataproc functions on WET files
├── sparktools
│   └── sparkhandler.py   : Lightweight wrapper for initializing Spark memory/CPU
├── get_data.sh           : Shell script to download path files from Common Crawl
└── README.md             : Project documentation
```
