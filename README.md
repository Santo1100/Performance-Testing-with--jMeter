# Performance-Testing-with--jMeter

Dear,

I’ve completed performance test on frequently used API for test App. Test executed for the below mentioned scenario in server 000.000.000.00.


200 Concurrent Request with 1 Loop Count; Avg TPS for Total Samples is ~ 13.34 And Total Concurrent API requested: 800.

300 Concurrent Request with 1 Loop Count; Avg TPS for Total Samples is ~ 40 And Total Concurrent API requested: 1600.

400 Concurrent Request with 1 Loop Count; Avg TPS for Total Samples is ~ 20 And Total Concurrent API requested: 1200.															 
600 Concurrent Request with 1 Loop Count; Avg TPS for Total Samples is ~ 60 And Total Concurrent API requested: 2400.


While executed 700 concurrent request, found 0 request got connection timeout and error rate is 0.00%
Summary: Server can handle almost concurrent 2000 API call with almost zero (0) error rate.
