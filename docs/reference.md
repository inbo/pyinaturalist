(reference-docs)=
# API Reference
iNaturalist currently provides three API versions:

* The original [Rails-based API](https://www.inaturalist.org/pages/api+reference) (v0)
  that they also use internally: it is very complete and provides read/write access, but has less
  consistent responses. It is likely that this API will be deprecated at some point in the future.
* The [Node-based API](https://api.inaturalist.org/v1/docs/) (v1) allows read and write access
  to most iNaturalist resources, and is generally faster and more consistent. It is
  missing some of the features of the v0 API, however.
* The [v2 API](https://api.inaturalist.org/v1/docs/) is currently in development, and will
  eventually replace both the v0 and v1 APIs. see
  [this forum thread](https://forum.inaturalist.org/t/obs-detail-on-api-v2-feedback/21215)
  if you are interested in testing it out.

Pyinaturalist provides functions to use the v0 and v1 APIs, with experimental v2 features coming soon.
Also see {ref}`endpoints` for an overview of which iNaturalist endpoints are currently implemented.

% Note: Source files for module docs are generated by sphinx-apidoc
```{toctree}
:caption: Main API Modules
:titlesonly: true

modules/pyinaturalist.v0
modules/pyinaturalist.v1
modules/pyinaturalist.v2
pyinaturalist.models
```

```{toctree}
:caption: Additional Utility Modules
:glob: true
:maxdepth: 1

modules/pyinaturalist.[!vm]*
```
