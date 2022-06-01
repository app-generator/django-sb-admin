# Change Log

## [1.0.4] 2022-06-01
### Improvements

- Built with [SB Admin Generator](https://appseed.us/generator/sb-admin/)
  - Timestamp: `2022-06-01 14:34`

## [1.0.3] 2022-01-20
### Improvements

- Bump Django Codebase to [v2stable.0.1](https://github.com/app-generator/boilerplate-code-django-dashboard/releases)
- Dependencies update (all packages) 
  - Django==4.0.1
- Settings update for Django 4.x
  - `New Parameter`: CSRF_TRUSTED_ORIGINS
    - [Origin header checking isn`t performed in older versions](https://docs.djangoproject.com/en/4.0/ref/settings/#csrf-trusted-origins)  

## [1.0.2] 2021-10-07
### Improvements

- Bump Django Codebase to [v2.0.4](https://github.com/app-generator/boilerplate-code-django-dashboard/releases)
- Dependencies update (all packages)
  - Use Django==3.2.6 (latest stable version)
- Better Code formatting
- Improved Files organization
- Optimize imports
- Docker Scripts Update 
- Tooling:
  - Gulp SASS compilation script   
  - `Update README` - Recompile SCSS (new section)
- Fixes: 
  - Patch 500 Error when authenticated users access `admin` path (no slash at the end)
  - Patch [#16](https://github.com/app-generator/boilerplate-code-django-dashboard/issues/16): Minor issue in Docker 

## [1.0.1] 2021-05-25
### Improvements

- Bump UI: [SB Admin](https://github.com/StartBootstrap/startbootstrap-sb-admin) v7.0.0
- UI Build Timestamp: 2021-05-25
- Codebase: [Django Boilerplate](https://github.com/app-generator/boilerplate-code-django-dashboard) v1.0.4 

## [1.0.0] 2020-09-01
### Initial Release
