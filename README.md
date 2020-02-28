# Core Flight System : Framework : App : Scheduler Lab

This repository contains NASA's Scheduler Lab (sch_lab), which is a framework component of the Core Flight System.

This lab application is a non-flight packet scheduler application for the cFS Bundle. It is intended to be located in the `apps/sch_lab` subdirectory of a cFS Mission Tree.  The Core Flight System is bundled at https://github.com/nasa/cFS (which includes sch_lab as a submodule), which includes build and execution instructions.

sch_lab is a simple packet scheduler application with a one second resoluton.

To change the list of packets that sch_lab sends out, edit the schedule table located in the platform include file:
fsw/platform_inc/sch_lab_sched_tab.h

## Version Notes
- 2.3.4: DEVELOPMENT
  - Fix for clean build with OMIT_DEPRECATED
  - Minor updates (see https://github.com/nasa/sch_lab/pull/35)
- 2.3.3: DEVELOPMENT
  - Minor updates (see https://github.com/nasa/sch_lab/pull/28)
- 2.3.2: DEVELOPMENT
  - Table definition include update (see https://github.com/nasa/sch_lab/pull/18)
- 2.3.1: DEVELOPMENT
  - Minor updates (see https://github.com/nasa/sch_lab/pull/16)
- **2.3.0 OFFICIAL RELEASE**:
  - Minor updates (see https://github.com/nasa/sch_lab/pull/13)
  - Not backwards compatible with OSAL 4.2.1
  - Released as part of cFE 6.7.0, Apache 2.0
- **2.2.0a OFFICIAL RELEASE**:
  - Released as part of cFE 6.6.0a, Apache 2.0

## Known issues

As a lab application, extensive testing is not performed prior to release and only minimal functionality is included.

## Getting Help

For best results, submit issues:questions or issues:help wanted requests at https://github.com/nasa/cFS.

Official cFS page: http://cfs.gsfc.nasa.gov  
