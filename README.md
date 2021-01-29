# RS Component Performance Test Assesment
============================================

### Tools and Plugins
============================================
  1. Jmeter 5.3.
  2. 3 Basic graphs plugin.
  3. Custom Thread Groups plugin.
  
### Assumptions
============================================
1. The TPS mentioned in the requirement was bit unclear on weather to achieve the Throughput ant the parent Transaction controller or the Total throuhput. hence i have used the total throughput available in the TOTAL column of the Summary report.

### Artifacts included in GitHub
============================================
1. RS-IRISH.jmx                     - Jmeter Script
2. Categories.csv                   - Test data file
3. PerfTestResults_ResultTree.jtl   - Result tree containing all the details of samples
4. PerfTestResults_Summary.jtl      - Summary of the load test
5. PerfTestResults_ResponseTime.jtl - Graph displaying the response time over time
6. PerfTestResults_TPS.jtl          - Graph displaying the TPS through out the test.

