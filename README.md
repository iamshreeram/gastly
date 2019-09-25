
<p align="center">
    <a href="#">
        <img src="static/images/gas.gif" />
    </a>
    <h3 align="center">gas.tly</h3>
    <h6 align="center">Framework for enhanced parallel Chaos Engineering</h6>
</p>


### chaos engineering 
is the discipline of experimenting on systems in order to build resilient application to withstand turbulent conditions in production.


### gas.tly
is the framework for enhanced chaos engineering. Current tools like `chaos monkey` have capacity produce a single point failure. `gas.tly` concentrates on creating multi-point failure parallelly and monitors the system behaviour for each failure.

### How does it work?
1. Gastly provides a solid time-series interface which will enable you to configure sequence of failures on different point of your distributed system.
2. Once the configurations are set, you can run gastly to poison the environment  
3. This also facilitates to poison environments randomly that are not configured
4. Gastly is equiped with agent to monitor the behaviour of poison points to give you summary of system resiliency score
5. Resiliency score is benchmarked and compared against the overall / multi-system score 
6. While poisoning the environment, `mey` agents will monitor and collect the metric changes to understand the weakness in resliency 
