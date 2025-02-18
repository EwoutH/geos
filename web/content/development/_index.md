---
title: "Development"
date: 2021-10-04T14:21:00-07:00
draft: false
---

## Developer Resources

* **git** repository: https://github.com/libgeos/geos
* [**geos-devel** mailing list](https://lists.osgeo.org/mailman/listinfo/geos-devel) and [archive](https://lists.osgeo.org/pipermail/geos-devel/)
* **#geos** chat channel:
  * Matrix: https://matrix.to/#/#geos:osgeo.org
  * Slack: https://osgeo.slack.com/messages/C07RKJ06B/


## Bug Reporting

Defects should be reported using
[GitHub Issues](https://github.com/libgeos/geos/issues).

When submitting bugs caused by particular geometries, you must
**submit the geometries that cause the failure**, preferably in hex-encoded
[WKB]({{< ref "../specifications/wkb" >}}), so that we can re-produce
the failure cases.


## Contributing

To contribute fixes to outstanding issues, enhancements, and other smaller
changes, open a [pull request](https://github.com/libgeos/geos/pulls) with
your change and a fullsome description of what you are trying to achieve.

If you have any doubts as to whether your work, or planned work,
is not a "smaller" change, please join the
[**geos-devel** mailing list](https://lists.osgeo.org/mailman/listinfo/geos-devel)
and describe your plans. **Join the list!** It is a great way to get
acquainted with what the development community is working on.


## Relationship to JTS

GEOS started as a direct port to C++ of the
[JTS Topology Suite](https://github.com/locationtech/jts/) (JTS),
and remains tightly bound to that project. Most core algorithms have
been prototyped in JTS and ported to GEOS when complete.

The projects attempt to share testing data, and to ascertain when failures
are caused by differences in implementation (GEOS fails and JTS does not)
and when they are caused by algorithm (both libraries fail).


## Governance

The GEOS project is run by a
[Project Steering Committee]({{< ref "psc" >}}) made up of developers
and contributors to the project and is a project of
[OSGeo](https://www.osgeo.org/projects/geos/).

