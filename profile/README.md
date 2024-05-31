# GEMS Sensing


# About GEMS Sensing
GEMS Sensing is a Service Organization of the [GEMS Informatics Center](https://gems.umn.edu)
at the University of Minnesota. Technologies are developed in the [Real-time GeoInformation Systems Lab](https://gems.umn.edu/runck-lab-real-time-geoinformation-systems) and supported by the [Minnesota Supercomputing Institute](https://www.msi.umn.edu).

# What GEMS Sensing Provides
GEMS Sensing provides:
1. A standard sensor data collection, integration, visualization, and download interface.
    - Hardware, see [here](https://docs.google.com/presentation/d/1kPZQUX78Zz0QIEOzYnMinlF56guJeX7Tj5Mpi_fBbqA/edit#slide=id.p)
    - Software, see [here](https://docs.google.com/presentation/d/1QI4CPYDpmwvkknx_j6gJL78oJswFsAZ1RGw0mIt8DoA/edit?usp=sharing)
    - Data Quality Assurance and Quality Control Flagging and more details, see [here](https://drive.google.com/file/d/19TvlmE-s2IM_KUYSgS6Zi3YtZK6CkIK5/view?usp=sharing)
3. Daily remote monitoring of each sensor in the field deployment, email notification if a sensor is down in your fleet, and remote technical support as you need it for solving the problem.
4. Templated standard operating procedures for managing the systems in the field. See [here](https://drive.google.com/drive/folders/1MkgD5a7tqKsihoUTgzv6W-Vz_hBZY4PG?usp=drive_link) for an example.

# What Hardware does GEMS Sensing Use?
See [here](https://docs.google.com/presentation/d/1kPZQUX78Zz0QIEOzYnMinlF56guJeX7Tj5Mpi_fBbqA/edit#slide=id.p).

The majority of our hardware is off-the-shelf from the best manufacturers of environmental sensors such as Apogee, Davis, and Acclima. 

# What does GEMS Sensing Cost?

These prices vary year to year, but here's a [sheet](https://docs.google.com/spreadsheets/d/1JM_3hssZ7EKTkJvvdXynYLw_Hqp4CS65hYAaL8H-5D8/edit#gid=0) to estimate for internal to UMN collaborations. If you're a non-UMN collaborator, we have to follow a different approach to establishing rates that ensures parity with the general market.

# What GEMS Sensing doesn't Provide:
We don't provide:
1. Full service field deployment and data collection. The [RTGS Lab](https://gems.umn.edu/runck-lab-real-time-geoinformation-systems) collaborates on research projects though at the co-PI and PI levels.
2. Consulting. We also do that through the RTGS Lab though.

# Can I interface new devices with your logger?
Yes! But this is an [RTGS Lab](https://gems.umn.edu/runck-lab-real-time-geoinformation-systems) project. We'll work with our sponsored project office to get things setup. We work with SDI-12, I2C, and analog devices.

# Does your system work in [Europe, Africa, Asia, ...]?
Likely, but not for certain. The Particle [B-Series SoM](https://docs.particle.io/b-series/) is the backbone of our logger and telemetry. We can swap out B-Series SoMs to work most places (see [here](https://docs.particle.io/reference/cellular/cellular-carriers/?tab=ByDevice&device=Tracker%20T404%2FONE404%20LTE%20M1%20(NorAm)%20EtherSIM&region=All), but we always recommend doing pilots if we haven't deployed in a location before.
