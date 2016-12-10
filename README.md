# Benchmarks of loggers for Golang

WIP. Benchmarks of loggers for Go language.


	BenchmarkLevelsKiwiTyped_Logfmt-4          	  100000	     17456 ns/op	    5700 B/op	     115 allocs/op
	BenchmarkLevelsKiwiTyped_JSON-4            	  100000	     24836 ns/op	    7097 B/op	     172 allocs/op
	BenchmarkLevelsKiwiTypedComplex_Logfmt-4   	   30000	     40939 ns/op	   11572 B/op	     216 allocs/op
	BenchmarkLevelsKiwiTypedComplex_JSON-4     	   30000	     44243 ns/op	   12622 B/op	     292 allocs/op
	BenchmarkLevelsKiwiTypedHelpers_Logfmt-4   	  100000	     18298 ns/op	    5523 B/op	     105 allocs/op
	BenchmarkLevelsKiwiTypedHelpers_JSON-4     	  100000	     21002 ns/op	    5813 B/op	     158 allocs/op
	BenchmarkLevelsKiwiTypedHelpersComplex-4   	   30000	     44389 ns/op	   12585 B/op	     288 allocs/op
	BenchmarkLevelsKiwi_Logfmt-4               	  100000	     18088 ns/op	    5658 B/op	     119 allocs/op
	BenchmarkLevelsKiwi_JSON-4                 	  100000	     21441 ns/op	    6612 B/op	     172 allocs/op
	BenchmarkLevelsKiwiComplex_Logfmt-4        	   30000	     43165 ns/op	   11545 B/op	     212 allocs/op
	BenchmarkLevelsKiwiComplex_JSON-4          	   30000	     42902 ns/op	   12582 B/op	     288 allocs/op
	BenchmarkLevelsKiwiGlobal_Logfmt-4         	  100000	     18900 ns/op	    5223 B/op	     150 allocs/op
	BenchmarkLevelsKiwiGlobal_JSON-4           	  100000	     22620 ns/op	    5934 B/op	     214 allocs/op
	BenchmarkLevelsStdLog_Text-4               	  100000	     23474 ns/op	    7159 B/op	     124 allocs/op
	BenchmarkLevelsStdLogComplex_Text-4        	   50000	     36390 ns/op	   11446 B/op	     200 allocs/op
	BenchmarkLevelsLogxi_Text-4                	  200000	     10391 ns/op	    2202 B/op	      58 allocs/op
	BenchmarkLevelsLogxi_JSON-4                	  100000	     14354 ns/op	    4127 B/op	      74 allocs/op
	BenchmarkLevelsLogxiComplex_Text-4         	   50000	     31740 ns/op	    8547 B/op	     158 allocs/op
	BenchmarkLevelsLogxiComplex_JSON-4         	   50000	     40308 ns/op	   10747 B/op	     182 allocs/op
	BenchmarkLevelsLogrus-4                    	   50000	     39728 ns/op	   12320 B/op	     177 allocs/op
	BenchmarkLevelsLogrusComplex-4             	   30000	     44268 ns/op	   13989 B/op	     231 allocs/op
	BenchmarkLevelsLog15_Logfmt-4              	   50000	     41176 ns/op	    9936 B/op	     220 allocs/op
	BenchmarkLevelsLog15_JSON-4                	   30000	     54571 ns/op	   14999 B/op	     224 allocs/op
	BenchmarkLevelsLog15Complex_Logfmt-4       	   20000	     67636 ns/op	   18555 B/op	     316 allocs/op
	BenchmarkLevelsLog15Complex_JSON-4         	   20000	     63302 ns/op	   18334 B/op	     300 allocs/op
	BenchmarkLevelsGokit_Logfmt-4              	  100000	     14924 ns/op	    2865 B/op	      64 allocs/op
	BenchmarkLevelsGokit_JSON-4                	   50000	     29377 ns/op	    7896 B/op	     160 allocs/op
	BenchmarkLevelsGokitComplex_Logfmt-4       	   50000	     38032 ns/op	    8768 B/op	     164 allocs/op
	BenchmarkLevelsGokitComplex_JSON-4         	   30000	     50349 ns/op	   12690 B/op	     248 allocs/op
