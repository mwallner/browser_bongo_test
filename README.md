# browser_bongo_test

simple performance benchmark / comparison of different browsers loading simple html/txt files

## Waterfox

| browser                | OS                | 256k txt | 512k txt | 1M txt | 2M txt | 10M txt | 20M txt | note                 |
| ---------------------- | ----------------- | -------- | -------- | ------ | ------ | ------- | ------- | -------------------- |
| Classic 2019.10 64-Bit | Win 1607 LTSB x64 | 240 ms   | 480 ms   | 240 ms | 640 ms | 1.92 s  | 2.56 s  | raw github, no cache |

## Firefox

| browser       | OS                | 256k txt | 512k txt | 1M txt | 2M txt | 10M txt | 20M txt | note                 |
| ------------- | ----------------- | -------- | -------- | ------ | ------ | ------- | ------- | -------------------- |
| 71.0 (64-bit) | Win 1607 LTSB x64 | 80 ms    | 80 ms    | 680 ms | 466 ms | 1.28 s  | 2.5 s   | raw github, no cache |

## Google Chrome

| browser               | OS                | 256k txt | 512k txt | 1M txt | 2M txt | 10M txt | 20M txt | note                 |
| --------------------- | ----------------- | -------- | -------- | ------ | ------ | ------- | ------- | -------------------- |
| 79.0.3945.79 (64-Bit) | Win 1607 LTSB x64 | 26 ms    | 506 ms   | 78 ms  | 670 ms | 46.39 s | 180 s   | raw github, no cache |

## Vivaldi

| browser              | OS                | 256k txt | 512k txt | 1M txt | 2M txt | 10M txt | 20M txt | note                 |
| -------------------- | ----------------- | -------- | -------- | ------ | ------ | ------- | ------- | -------------------- |
| 2.7.1628.30 (64-Bit) | Win 1607 LTSB x64 | 20 ms    | 334 ms   | 321 ms | 1.38 s | 36.8 s  | 149 s   | raw github, no cache |
