# cdm-etl

**The first prototype of this componet is expect to be ready by August 2024**

The OpenCDMS - Extract Transform Load (CDM-ETL) component can be used with any Climate Data Management System (CDMS) that implements the OpenCDMS API for interacting with the WMO Core Climate Data Model - Observations (WCCDM-OBS) standard that is under development by the WMO Task Team on Climate Data Model (TT-CDM). See [OpenCDMS](http://github.com/opencdms/opencdms) (also under development) for a Reference Implementation of the Climate Data Model Standard and OpenCDMS API.

OpenCDMS-ETL allow you to:
1. **Extact** data from any system implementing the CDM APIs
2. **Transform** the data by passing it to a OGC API Processes process
3. **Load** the data by specifying where/how you want the resulting output

The OpenCDMS-ETL repository will contain:
1. A framework independent reuseable W3C web componet (developed with Stencil and Ionic Framework), available from npm
2. A reusable OGC API - Processes process (developmed with Python 3), available from PyPI
3. Documentation
4. Tests
