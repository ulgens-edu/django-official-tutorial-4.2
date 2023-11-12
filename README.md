# Simple Django Project from Official Django Tutorials

I like to revisit https://docs.djangoproject.com/ tutorials from time to time, to refresh my memory about the fundamentals. The code/project under this repo is based on the 7 Nov 2023 dated version of the docs.

The completed version of each tutorial has a tag named `tutorial<tut_number>`.

The final version of the repo includes some improvements I like to apply to all my Django projects:

* Poetry setup.
* Pre-commit setup with `pre-commit-hooks`, `black`, `flake8` (including multiple additional dependencies), `yesqa`, `isort`, `pyupgrade`, `django-upgrade` and `bandit`.
* Renaming of default Django projects folder. The wording is open to discussion but I think `src/core` is much more appropriate for what those folders do, compared to `<project_name>/<project_name>`.
