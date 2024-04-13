# gitlabci manager multidoc yaml

With gitlabs new CI Components gitlab-ci files can be multidocument yaml ([docs](https://docs.gitlab.com/ee/ci/yaml/inputs.html#define-input-parameters-with-specinputs)). Renovate currently fails parsing multidocument gitlab-ci files.  

Something like https://github.com/renovatebot/renovate/pull/8828/files is needed
