# GANGLIA MONITOR CORE

Forked from [ganglia/monitor-core](https://github.com/ganglia/monitor-core) via [efposadac/monitor-core](https://github.com/efposadac/monitor-core) which implemented python3 patches.

## rpmbuild_alma9 branch
* Fixes `ganglia.spec.in` for rpmbuild on Alma Linux 9 and compatible EL9
* Adds custom `ganglia_atds.spec.in` file for legacy compatibility (derived from old EPEL spec), to support [@AtlasTdaqSysAdmins](https://github.com/AtlasTdaqSysAdmins)
  in the migration to Alma Linux 9 and Prometheus/Grafana
* Adds automated GitHub Actions for building RPM packages for Alma Linux 9,
  using a fork of [naveenrajm7/rpmbuild](https://github.com/marketplace/actions/rpm-build) adapted for Alma9 and some additional functionality

# Original README.md

[![Build Status](https://secure.travis-ci.org/ganglia/monitor-core.png)](http://travis-ci.org/ganglia/monitor-core)
