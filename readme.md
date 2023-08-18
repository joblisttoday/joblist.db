# joblist.today sqlite3

1. https://github.com/joblisttoday/data is used as "source of truth" for joblist day; wikipedia styles of edit transparency, in git, folder and files, editable as text, or through the cms https://gitlab.com/joblist/cms
2. the workers https://gitlab.com/joblist/workers generate a gitlab artifact for the `joblist.db`, hosted on the gitlab pages https://joblist.gitlab.io/workers/joblist.db, so it can be used in (node and) the browser with https://github.com/phiresky/sql.js-httpvfs

This repositoy is a convenience to access all "data formats" for joblist, on github
