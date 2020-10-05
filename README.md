# LTEV2Vsim

LTEV2Vsim is a dynamic simulator, written in MATLAB, designed for the investigation of resource allocation in LTE-V2V networks, with focus on the cooperative awareness service. Since version 3.0, LTEV2Vsim also allows to simulate the cooperative awareness service using IEEE 802.11p/ITS-G5.

The simulator is shared under the GNU GPLv3.

The software has been developed and shared by University of Bologna, CNR, and CNIT - Italy. A web page was set up at http://www.wcsg.ieiit.cnr.it/products/LTEV2Vsim.html (since January 2020, download of code and files from there are not available - information inside that page might also not be always up-to-date)

Before version 5.0, the simulator was based on a "beacon period" timing, which was a trade-off between accuracy and speed. Starting from version 5.0, the time granularity has been reduced to 1 ms in order to allow simulating more cases, including traffic generation with non-uniform-periodic characteristics. Additionaly, whereas before version 5.0 there were two separate main files for LTE-V2X and IEEE 802.11p, since verison 5.0 there is a single main, allowing simulating both technologies at the same time.
Version 5.4 (uploaded in October 2020) comes with a number of improvements related to both sidelink LTE-V2X and IEEE 802.11p. For details, please refer to the read-me document which is available within the compressed file.

NOTICE: at least MATLAB R2016b is required.

The structure and features of the simulator, along with its main inputs and outputs, are described in

G. Cecchini, A. Bazzi, B. M. Masini, A. Zanella, “LTEV2Vsim: An LTE-V2V Simulator for the Investigation of Resource Allocation for Cooperative Awareness”, 5th IEEE International Conference on Models and Technologies for Intelligent Transportation Systems (MT-ITS 2017), Naples (Italy), 26-28 June 2017. Accepted version here. (Results obtained with version 1.0)

A. Bazzi, G. Cecchini, M. Menarini, B. M. Masini, A. Zanella, “Survey and Perspectives of Vehicular Wi-Fi Versus Sidelink Cellular-V2X in the 5G Era,” invited paper in Future Internet, 29 May 2019, 11(6), 122. DOI: 10.3390/fi11060122 Open access here. (Results obtained with version 3.5)
