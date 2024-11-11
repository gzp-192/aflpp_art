./afl-fuzz -i /out/seeds -o /out/corpus -m none -t 1000+ -d -Q -c0 -a -- /out/fuzz_target 2147483647

-a:使用ART种子调度