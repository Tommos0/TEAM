# CWL (Niels)

The CWL team will be working on Common Workflow Language (http://www.commonwl.org/) related software. As the CWL ecosystem is growing, we have quite a few options (incomplete list here https://github.com/NLeSC/?utf8=%E2%9C%93&q=cwl&type=&language=).

It is early days in the CWL ecosystem. Some libraries and tools could get a large userbase and influence CWL itself as a result.

Team members get a say on what we work on :-)

- pyCWL: Python library for CWL. Should be able to parse, verify, build programmatically, save, and run CWL workflows. All without leaving python.
- tinycwl: Very small CWL implementation by Lourens (developed as part of Cerise). Could probably best be integrated with pyCWL.
- A standalone multithreaded CWL runner (Also to be integrated with pyCWL).
- cwl4j: Java library for CWL. Should be able to parse, verify, build programmatically, save, and run CWL workflows. Potentially a second reference implementation of CWL(!).
- cwl-compute-api. A spec for running CWL workflows via a REST API. Used in Xenon-Flow and Cerise. Needs a new GitHub location, perhaps some documentation, etc.
- Xenon-Flow: Xenon/Swagger/Spring/Hibernate based REST service for running CWL workflows. Used in the CommonSense team, so would be a nice cross-team cooperation.
- Cerise: Python based REST service for running CWL workflows. Uses Xenon.

For the second sprint (November) we will be working on scriptcwl (https://github.com/NLeSC/scriptcwl), as Janneke (the lead developer) is on holiday.


