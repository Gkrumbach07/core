<!---
This is an autogenerated file!

Please do not edit this file directly, but instead make changes to the
sigs.yaml file in the project root.

To understand how this file is generated, see https://git.k8s.io/community/generator/README.md

for Thoth we use `podman run --rm -e WHAT -e GO111MODULE=on -e GOPROXY -v $(pwd):/go/src/app:Z golang:1.12 make -C /go/src/app generate`

--->

# DevSecOps Special Interest Group

This SIG covers all the tools and supporting container images that deliver Thoth-Station applications, as well as the build pipelines and Continuous Integration systems that enable the automated builds.
This includes the discussion related to the release process of the Thoth-Station applications, the build pipelines themselves, supporting container images, tooling, and architectural decisions.

The [charter](charter.md) defines the scope and governance of the DevSecOps Special Interest Group.

## Meetings
* Thoth DevSecOps Meeting: [Thursdays at 15:30 UTC (Coordinated Universal Time)](https://meet.google.com/ozb-tbrp-agx) (weekly). [Convert to your timezone](http://www.thetimezoneconverter.com/?t=15:30&tz=UTC%20%28Coordinated%20Universal%20Time%29).
  * [Meeting notes and Agenda](https://docs.google.com/document/d/16EIdTs12apkjuNlgBCMa0gQ2Gd0CFu9wn-N9GQmwTdw/edit).

## Leadership

### Chairs

The Chairs of the SIG run operations and processes governing the SIG.

* Harshad Nalla (**[@harshad16](https://github.com/harshad16)**), Red Hat

### Technical Leads

The Technical Leads of the SIG establish new subprojects, decommission existing
subprojects, and resolve cross-subproject technical issues and decisions.

* Harshad Nalla (**[@harshad16](https://github.com/harshad16)**), Red Hat

## Contact
- [Open Community Issues/PRs](https://github.com/kubernetes/community/labels/sig%2Fdevsecops)
- Steering Committee Liaison: Christoph Görn (**[@goern](https://github.com/goern)**)

## Subprojects

The following [subprojects][subproject-definition] are owned by sig-devsecops:
### Notebooks
A set of base images that are useful for Data Science work
- **Owners:**
  - https://raw.githubusercontent.com/thoth-station/ps-cv/master/OWNERS
  - https://raw.githubusercontent.com/thoth-station/ps-ip/master/OWNERS
  - https://raw.githubusercontent.com/thoth-station/ps-nlp/master/OWNERS
  - https://raw.githubusercontent.com/thoth-station/ray-ml-notebook/master/OWNERS
  - https://raw.githubusercontent.com/thoth-station/ray-ml-worker/master/OWNERS
  - https://raw.githubusercontent.com/thoth-station/ray-operator/master/OWNERS
  - https://raw.githubusercontent.com/thoth-station/s2i-data-science-notebook/master/OWNERS
  - https://raw.githubusercontent.com/thoth-station/s2i-minimal-notebook/master/OWNERS
  - https://raw.githubusercontent.com/thoth-station/s2i-pytorch-notebook/master/OWNERS
  - https://raw.githubusercontent.com/thoth-station/s2i-scipy-notebook/master/OWNERS
  - https://raw.githubusercontent.com/thoth-station/s2i-tensorflow-gpu-notebook/master/OWNERS
  - https://raw.githubusercontent.com/thoth-station/s2i-tensorflow-notebook/master/OWNERS
### Pipelines
A set of base images and pipelines to build application container images
- **Owners:**
  - https://raw.githubusercontent.com/AICoE/aicoe-ci/master/OWNERS
  - https://raw.githubusercontent.com/thoth-station/helm-charts/master/OWNERS
  - https://raw.githubusercontent.com/thoth-station/jupyternb-build-pipeline/master/OWNERS
  - https://raw.githubusercontent.com/thoth-station/pipeline-helpers/master/OWNERS
### Services
Tooling and configuration to manage the releases of various Thoth services and components
- **Owners:**
  - https://raw.githubusercontent.com/AICoE/sefkhet-abwy/master/OWNERS
  - https://raw.githubusercontent.com/thoth-station/s2i-thoth/master/OWNERS
  - https://raw.githubusercontent.com/thoth-station/thoth-application/master/OWNERS
  - https://raw.githubusercontent.com/thoth-station/thoth-ops-infra/master/OWNERS
  - https://raw.githubusercontent.com/thoth-station/thoth-ops/master/OWNERS
  - https://raw.githubusercontent.com/thoth-station/thoth-toolbox/master/OWNERS

[subproject-definition]: https://github.com/kubernetes/community/blob/master/governance.md#subprojects
<!-- BEGIN CUSTOM CONTENT -->

<!-- END CUSTOM CONTENT -->
