This document is a declaration of software quality for **eProsima FastCDR** based on the guidelines provided in the [ROS
2 REP-2004 document](https://www.ros.org/reps/rep-2004.html).

Quality Declaration
=============================

**eProsima FastCDR** is a C++ library that provides two serialization mechanisms. One is the [standard
CDR](https://www.omg.org/cgi-bin/doc?formal/02-06-51) serialization mechanism, while the other is a faster
implementation that modifies the standard.

**eProsima FastCDR** claims to be in the **Quality Level 4** category.

Below are the rationales, notes and caveats for this claim, organized by each requirement listed in the [Package
Requirements for Quality Level 1 in REP-2004](https://www.ros.org/reps/rep-2004.html#package-requirements).

## Version Policy [1]

### Version Scheme [1.i]

Currently **eProsima FastCDR** does not have a public Version Policy.

### Version Stability [1.ii]

**eProsima FastCDR** is at a stable version, i.e. `>=1.0.0`.
The latest version can be found [here](https://github.com/eProsima/Fast-CDR/releases).

[//]: # (TODO JLBuenoLopez-eProsima There is no public change history in the repository. However, the release notes are
public from version v1.0.8 to the latest.)

### Public API Declaration [1.iii]

Although **eProsima FastCDR** used to generate the documentation using doxygen, currently the CMakeLists.txt is not
prepared to build the documentation when the CMake options `BUILD_DOCUMENTATION` and/or `CHECK_DOCUMENTATION` are set.
eProsima webpage hosts the [**eProsima FastCDR** v0.3.0
documentation](https://www.eprosima.com/docs/fast-buffers/0.3.0/html/index.html) which is outdated with respect to the
current version 1.0.15. This old documentation includes the [Common API
Reference](https://www.eprosima.com/docs/fast-buffers/0.3.0/html/group___f_a_s_t_c_d_r_a_p_i_r_e_f_e_r_e_n_c_e.html).

[//]: # (TODO JLBuenoLopez-eProsima [Issue 60](https://github.com/eProsima/Fast-CDR/issues/60) shows how confusing is
the current lack of documentation)

### API Stability Policy [1.iv]

Currently **eProsima FastCDR** does not have any public Version Policy.

### ABI Stability Policy [1.v]

Currently **eProsima FastCDR** does not have any public Version Policy.

## API and ABI Stability Within a Released ROS Distribution [1.vi]

[//]: # (TODO JLBuenoLopez-eProsima This specific point is so ROS related that maybe it does not make sense to keep in
this Declaration. The external declaration for ROS will consider if we meet his specifications)

## Change Control Process [2]

The stability of **eProsima FastCDR** is ensured through reviews, CI and tests. All commits must be signed by the author
as stated in [CONTRIBUTING](CONTRIBUTING.md) since version 1.0.14.








PENDING:

* **eProsima FastCDR** does not have a code style and does not enforce it. The code style is only enforced for *eprosima
  Fast DDS*.