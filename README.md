# IsoVista

## Known limitations

- Currently the implementation of PolySI+ might not be very robust, potentially resulting in a small chance of false positives.
- If the workload parameter is set very high (e.g., #session=10000), it might lead to the exhaustion of system resources, so IsoVista have imposed limits on the size of some parameters.
- IsoVista use numerous network connections for the transmission of data between the frontend and backend. If the network is congested, it might cause charts or tables to not display promptly.
