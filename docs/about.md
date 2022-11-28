# Installing MkDocs etc.

## Shell log
    21:40: mkdocs ⧝ pip install mkdocs
    Collecting mkdocs
    Downloading mkdocs-1.4.2-py3-none-any.whl (3.7 MB)
        ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 3.7/3.7 MB 2.3 MB/s eta 0:00:00
    Collecting click>=7.0
    Downloading click-8.1.3-py3-none-any.whl (96 kB)
        ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 96.6/96.6 kB 1.9 MB/s eta 0:00:00
    Collecting ghp-import>=1.0
    Downloading ghp_import-2.1.0-py3-none-any.whl (11 kB)
    Collecting jinja2>=2.11.1
    Downloading Jinja2-3.1.2-py3-none-any.whl (133 kB)
        ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 133.1/133.1 kB 1.5 MB/s eta 0:00:00
    Collecting markdown<3.4,>=3.2.1
    Downloading Markdown-3.3.7-py3-none-any.whl (97 kB)
        ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 97.8/97.8 kB 3.2 MB/s eta 0:00:00
    Collecting mergedeep>=1.3.4
    Downloading mergedeep-1.3.4-py3-none-any.whl (6.4 kB)
    Collecting packaging>=20.5
    Downloading packaging-21.3-py3-none-any.whl (40 kB)
        ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 40.8/40.8 kB 858.9 kB/s eta 0:00:00
    Collecting pyyaml-env-tag>=0.1
    Downloading pyyaml_env_tag-0.1-py3-none-any.whl (3.9 kB)
    Collecting pyyaml>=5.1
    Downloading PyYAML-6.0-cp311-cp311-manylinux_2_17_x86_64.manylinux2014_x86_64.whl (757 kB)
        ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 757.9/757.9 kB 3.5 MB/s eta 0:00:00
    Collecting watchdog>=2.0
    Downloading watchdog-2.1.9-py3-none-manylinux2014_x86_64.whl (78 kB)
        ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 78.4/78.4 kB 2.9 MB/s eta 0:00:00
    Collecting python-dateutil>=2.8.1
    Downloading python_dateutil-2.8.2-py2.py3-none-any.whl (247 kB)
        ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 247.7/247.7 kB 3.8 MB/s eta 0:00:00
    Collecting MarkupSafe>=2.0
    Downloading MarkupSafe-2.1.1.tar.gz (18 kB)
    Preparing metadata (setup.py) ... done
    Collecting pyparsing!=3.0.5,>=2.0.2
    Downloading pyparsing-3.0.9-py3-none-any.whl (98 kB)
        ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 98.3/98.3 kB 2.6 MB/s eta 0:00:00
    Collecting six>=1.5
    Using cached six-1.16.0-py2.py3-none-any.whl (11 kB)
    Installing collected packages: watchdog, six, pyyaml, pyparsing, mergedeep, MarkupSafe, markdown, click, pyyaml-env-tag, python-dateutil, packaging, jinja2, ghp-import, mkdocs
    DEPRECATION: MarkupSafe is being installed using the legacy 'setup.py install' method, because it does not have a 'pyproject.toml' and the 'wheel' package is not installed. pip 23.1 will enforce this behaviour change. A possible replacement is to enable the '--use-pep517' option. Discussion can be found at https://github.com/pypa/pip/issues/8559
    Running setup.py install for MarkupSafe ... done
    Successfully installed MarkupSafe-2.1.1 click-8.1.3 ghp-import-2.1.0 jinja2-3.1.2 markdown-3.3.7 mergedeep-1.3.4 mkdocs-1.4.2 packaging-21.3 pyparsing-3.0.9 python-dateutil-2.8.2 pyyaml-6.0 pyyaml-env-tag-0.1 six-1.16.0 watchdog-2.1.9
    (mkenv) 
    21:40: mkdocs ⧝ pip install click-man
    Collecting click-man
    Downloading click_man-0.4.1-py3-none-any.whl (9.1 kB)
    Requirement already satisfied: click in ./mkenv/lib64/python3.11/site-packages (from click-man) (8.1.3)
    Installing collected packages: click-man
    Successfully installed click-man-0.4.1
    (mkenv) 
    21:41: mkdocs ⧝ click-man --target path/to/man/pages mkdocs
    Load entry point mkdocs
    Generate man pages for mkdocs in /media/john/sys2/web18/playground/python/mkdocs/path/to/man/pages
    (mkenv) 
    21:41: mkdocs ⧝ mkdocs new test-project_00
    INFO     -  Creating project directory: test-project_00
    INFO     -  Writing config file: test-project_00/mkdocs.yml
    INFO     -  Writing initial docs: test-project_00/docs/index.md
    (mkenv) 
    21:42: mkdocs ⧝ cd test-project_00/
    (mkenv) 
    21:42: test-project_00 ⧝ ls
    docs  mkdocs.yml
    (mkenv) 
    21:42: test-project_00 ⧝ cat mkdocs.yml 
    site_name: My Docs
    (mkenv) 
    21:42: test-project_00 ⧝ ls
    docs  mkdocs.yml
    (mkenv) 
    21:45: test-project_00 ⧝ ls docs/
    index.md
    (mkenv) 
    21:45: test-project_00 ⧝ mkdo
    mkdocs   mkdosfs  
    (mkenv) 
    21:45: test-project_00 ⧝ mkdocs serve
    INFO     -  Building documentation...
    INFO     -  Cleaning site directory
    INFO     -  Documentation built in 0.25 seconds
    INFO     -  [21:46:20] Watching paths for changes: 'docs', 'mkdocs.yml'
    INFO     -  [21:46:20] Serving on http://127.0.0.1:8000/
            INFO     -  [21:46:49] Browser connected: http://127.0.0.1:8000/
    INFO     -  [21:51:56] Detected file changes
    INFO     -  Building documentation...
    INFO     -  [21:51:57] Reloading browsers
    INFO     -  [21:51:58] Browser connected: http://127.0.0.1:8000/
    INFO     -  [21:53:23] Browser connected: http://127.0.0.1:8000/
    INFO     -  [21:53:53] Detected file changes
    INFO     -  Building documentation...
    INFO     -  [21:53:54] Reloading browsers
    INFO     -  [21:53:54] Browser connected: http://127.0.0.1:8000/
    INFO     -  [21:54:09] Detected file changes
    INFO     -  Building documentation...
    INFO     -  [21:54:10] Reloading browsers
    INFO     -  [21:54:10] Browser connected: http://127.0.0.1:8000/
    INFO     -  [21:56:43] Detected file changes
    INFO     -  Building documentation...
    WARNING  -  Config value 'site-url': Unrecognised configuration name: site-url
    INFO     -  [21:56:44] Reloading browsers
    INFO     -  [21:56:44] Browser connected: http://127.0.0.1:8000/
    INFO     -  [21:56:54] Browser connected: http://127.0.0.1:8000/
    INFO     -  [21:57:27] Detected file changes
    INFO     -  Building documentation...
    WARNING  -  Config value 'site-url': Unrecognised configuration name: site-url
    INFO     -  [21:57:27] Reloading browsers
    INFO     -  [21:57:27] Browser connected: http://127.0.0.1:8000/
    INFO     -  [21:57:28] Detected file changes
    INFO     -  Building documentation...
    WARNING  -  Config value 'site-url': Unrecognised configuration name: site-url
    INFO     -  [21:57:28] Reloading browsers
    INFO     -  [21:57:28] Browser connected: http://127.0.0.1:8000/
    INFO     -  [21:58:17] Detected file changes
    INFO     -  Building documentation...
    WARNING  -  Config value 'site-url': Unrecognised configuration name: site-url
    INFO     -  [21:58:18] Reloading browsers
    INFO     -  [21:58:18] Browser connected: http://127.0.0.1:8000/
    INFO     -  [21:58:28] Browser connected: http://127.0.0.1:8000/about/
    INFO     -  [21:59:28] Browser connected: http://127.0.0.1:8000/
    INFO     -  [21:59:31] Browser connected: http://127.0.0.1:8000/about/
    INFO     -  [21:59:40] Browser connected: http://127.0.0.1:8000/
    INFO     -  [22:00:41] Detected file changes
    INFO     -  Building documentation...
    WARNING  -  Config value 'site-url': Unrecognised configuration name: site-url
    INFO     -  [22:00:42] Reloading browsers
    INFO     -  [22:00:42] Browser connected: http://127.0.0.1:8000/
    INFO     -  [22:00:53] Browser connected: http://127.0.0.1:8000/about/
    INFO     -  [22:14:36] Detected file changes
    INFO     -  Building documentation...
    WARNING  -  Config value 'site-url': Unrecognised configuration name: site-url
    INFO     -  [22:14:37] Reloading browsers
    INFO     -  [22:14:38] Browser connected: http://127.0.0.1:8000/
    INFO     -  [22:14:57] Detected file changes
    INFO     -  Building documentation...
    WARNING  -  Config value 'site-url': Unrecognised configuration name: site-url
    INFO     -  [22:14:57] Reloading browsers
    INFO     -  [22:14:58] Browser connected: http://127.0.0.1:8000/
    INFO     -  [22:16:11] Detected file changes
    INFO     -  Building documentation...
    WARNING  -  Config value 'site-url': Unrecognised configuration name: site-url
    INFO     -  [22:16:12] Reloading browsers
    INFO     -  [22:16:12] Browser connected: http://127.0.0.1:8000/
    INFO     -  [22:22:58] Detected file changes
    INFO     -  Building documentation...
    WARNING  -  Config value 'site-url': Unrecognised configuration name: site-url
    INFO     -  [22:22:59] Reloading browsers
    INFO     -  [22:22:59] Browser connected: http://127.0.0.1:8000/
    INFO     -  [22:23:20] Detected file changes
    INFO     -  Building documentation...
    WARNING  -  Config value 'site-url': Unrecognised configuration name: site-url
    INFO     -  [22:23:21] Reloading browsers
    INFO     -  [22:23:21] Browser connected: http://127.0.0.1:8000/
    INFO     -  [22:25:48] Detected file changes
    INFO     -  Building documentation...
    WARNING  -  Config value 'site-url': Unrecognised configuration name: site-url
    INFO     -  [22:25:49] Reloading browsers
    INFO     -  [22:25:49] Browser connected: http://127.0.0.1:8000/
    INFO     -  [22:30:55] Detected file changes
    INFO     -  Building documentation...
    WARNING  -  Config value 'site-url': Unrecognised configuration name: site-url
    INFO     -  [22:30:55] Reloading browsers
    INFO     -  [22:30:55] Browser connected: http://127.0.0.1:8000/
    INFO     -  [22:32:09] Detected file changes
    INFO     -  Building documentation...
    WARNING  -  Config value 'site-url': Unrecognised configuration name: site-url
    INFO     -  [22:32:09] Reloading browsers
    INFO     -  [22:32:09] Browser connected: http://127.0.0.1:8000/
    INFO     -  [22:32:52] Browser connected: http://127.0.0.1:8000/about/
    INFO     -  [22:33:00] Browser connected: http://127.0.0.1:8000/
    ^CINFO     -  Shutting down...
    (mkenv) 
    22:34: test-project_00 ⧝ mkdocs build
    WARNING  -  Config value 'site-url': Unrecognised configuration name: site-url
    INFO     -  Cleaning site directory
    INFO     -  Building documentation to directory: /media/john/sys2/web18/playground/python/mkdocs/test-project_00/site
    INFO     -  Documentation built in 0.09 seconds
    (mkenv) 
    22:34: test-project_00 ⧝ tree
    .
    ├── docs
    │   ├── about.md
    │   ├── img
    │   │   ├── favicon.ico
    │   │   ├── td_logo.png
    │   │   └── tnd_logo.ico
    │   └── index.md
    ├── mkdocs.yml
    └── site
        ├── 404.html
        ├── about
        │   └── index.html
        ├── css
        │   ├── fonts
        │   │   ├── fontawesome-webfont.eot
        │   │   ├── fontawesome-webfont.svg
        │   │   ├── fontawesome-webfont.ttf
        │   │   ├── fontawesome-webfont.woff
        │   │   ├── fontawesome-webfont.woff2
        │   │   ├── lato-bold-italic.woff
        │   │   ├── lato-bold-italic.woff2
        │   │   ├── lato-bold.woff
        │   │   ├── lato-bold.woff2
        │   │   ├── lato-normal-italic.woff
        │   │   ├── lato-normal-italic.woff2
        │   │   ├── lato-normal.woff
        │   │   ├── lato-normal.woff2
        │   │   ├── Roboto-Slab-Bold.woff
        │   │   ├── Roboto-Slab-Bold.woff2
        │   │   ├── Roboto-Slab-Regular.woff
        │   │   └── Roboto-Slab-Regular.woff2
        │   ├── theme.css
        │   └── theme_extra.css
        ├── img
        │   ├── favicon.ico
        │   ├── td_logo.png
        │   └── tnd_logo.ico
        ├── index.html
        ├── js
        │   ├── html5shiv.min.js
        │   ├── jquery-3.6.0.min.js
        │   ├── theme_extra.js
        │   └── theme.js
        ├── search
        │   ├── lunr.js
        │   ├── main.js
        │   ├── search_index.json
        │   └── worker.js
        ├── search.html
        ├── sitemap.xml
        └── sitemap.xml.gz

    9 directories, 42 files
    (mkenv) 
    22:34: test-project_00 ⧝ git init
    Initialized empty Git repository in /media/john/sys2/web18/playground/python/mkdocs/test-project_00/.git/
    (mkenv) 
    22:36: test-project_00 ⧝ echo "site/" >> .gitignore
    (mkenv) 
    22:36: test-project_00 ⧝ git remote add origin git@github.com:teraspora/tnd.git
    (mkenv) 
    22:38: test-project_00 ⧝ git branch -M main
    (mkenv) 
    22:38: test-project_00 ⧝ git push -u origin main
    error: src refspec main does not match any
    error: failed to push some refs to 'github.com:teraspora/tnd.git'
    (mkenv) 
    22:39: test-project_00 ⧝ gs
    On branch main

    No commits yet

    Untracked files:
    (use "git add <file>..." to include in what will be committed)
        .gitignore
        docs/
        mkdocs.yml

    nothing added to commit but untracked files present (use "git add" to track)
    (mkenv) 
    22:39: test-project_00 ⧝ echo ".gitignore" >> .gitignore
    (mkenv) 
    22:39: test-project_00 ⧝ gs
    On branch main

    No commits yet

    Untracked files:
    (use "git add <file>..." to include in what will be committed)
        docs/
        mkdocs.yml

    nothing added to commit but untracked files present (use "git add" to track)
    (mkenv) 
    22:39: test-project_00 ⧝ ll
    total 28K
    drwxr-xr-x 5 john john 4.0K Nov 28 22:36 ./
    drwxr-xr-x 5 john john 4.0K Nov 28 21:42 ../
    drwxr-xr-x 3 john john 4.0K Nov 28 22:14 docs/
    drwxr-xr-x 7 john john 4.0K Nov 28 22:39 .git/
    -rw-r--r-- 1 john john   17 Nov 28 22:39 .gitignore
    -rw-r--r-- 1 john john  145 Nov 28 22:25 mkdocs.yml
    drwxr-xr-x 7 john john 4.0K Nov 28 22:34 site/
