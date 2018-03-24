# Report for tests performed on 2018-03-24

## [https://hollowverse.com](https://hollowverse.com)

### Security Headers

| URL                     | Grade |
| ----------------------- | ----- |
| https://hollowverse.com | A     |

### [WebPageTest](http://www.webpagetest.org/results.php?test=180324_SE_cc52aa75d7b9ca15cf775a5a66b6d546)

| Test                       | First View | Repeat View |
| -------------------------- | ---------- | ----------- |
| Number of requests         | 85         | 33          |
| Time to first byte         | 1.49s      | 1.57s       |
| Fully loaded               | 11.40s     | 12.33s      |
| Response size              | 1194.33KiB | 221.62KiB   |
| Response size (compressed) | 842.79KiB  | 212.47KiB   |

### Lighthouse via WebPageTest

| Test                     | First View | Repeat View |
| ------------------------ | ---------- | ----------- |
| Performance              | 40%        | 40%         |
| First Meaningful Paint   | 5.27s      | 5.27s       |
| First Interactive        | 11.92s     | 11.92s      |
| Consistently Interactive | 11.92s     | 11.92s      |
| Speed Index Metric       | 9435       | 9435        |
| Estimated Input Latency  | 0.03s      | 0.03s       |
| PWA                      | 45%        | 45%         |
| Accessibility            | 92%        | 92%         |
| Best Practices           | 81%        | 81%         |
| SEO                      | 89%        | 89%         |

### Mobile Friendliness

| Test                                                         | Status                    |
| ------------------------------------------------------------ | ------------------------- |
| Is page mobile friendly?                                     | Yes :heavy_check_mark:    |
| Does not use plugins incompatible with mobile devices        | Passed :heavy_check_mark: |
| Viewport is specified using the meta viewport tag            | Passed :heavy_check_mark: |
| Viewport is not defined to a fixed width                     | Passed :heavy_check_mark: |
| Content is sized to viewport                                 | Passed :heavy_check_mark: |
| Font size is large enough for easy reading on a small screen | Passed :heavy_check_mark: |
| Touch elements are not too close to each other               | Passed :heavy_check_mark: |

### Elastic Beanstalk

| Environment                        | Health                |
| ---------------------------------- | --------------------- |
| hollowverse-release-manager-master | :heavy_check_mark: OK |
| hollowverse-beta                   | :heavy_check_mark: OK |
| hollowverse-master                 | :heavy_check_mark: OK |
| hollowverse-new-app                | :heavy_check_mark: OK |
| hollowverse-api-master             | :heavy_check_mark: OK |

## [https://hollowverse.com/Tom_Hanks](https://hollowverse.com/Tom_Hanks)

### Security Headers

| URL                               | Grade |
| --------------------------------- | ----- |
| https://hollowverse.com/Tom_Hanks | N/A   |

### [WebPageTest](http://www.webpagetest.org/results.php?test=180324_33_9f64773b0663a88fdff4929200f088c0)

| Test                       | First View | Repeat View |
| -------------------------- | ---------- | ----------- |
| Number of requests         | 16         | 2           |
| Time to first byte         | 1.50s      | 1.49s       |
| Fully loaded               | 4.39s      | 2.53s       |
| Response size              | 205.91KiB  | 8.08KiB     |
| Response size (compressed) | 169.69KiB  | 7.75KiB     |

### Lighthouse via WebPageTest

| Test                     | First View | Repeat View |
| ------------------------ | ---------- | ----------- |
| Performance              | 72%        | 72%         |
| First Meaningful Paint   | 3.67s      | 3.67s       |
| First Interactive        | 5.61s      | 5.61s       |
| Consistently Interactive | 5.61s      | 5.61s       |
| Speed Index Metric       | 3964       | 3964        |
| Estimated Input Latency  | 0.02s      | 0.02s       |
| PWA                      | 55%        | 55%         |
| Accessibility            | 97%        | 97%         |
| Best Practices           | 94%        | 94%         |
| SEO                      | 90%        | 90%         |

### Mobile Friendliness

| Test                                                         | Status                    |
| ------------------------------------------------------------ | ------------------------- |
| Is page mobile friendly?                                     | Yes :heavy_check_mark:    |
| Does not use plugins incompatible with mobile devices        | Passed :heavy_check_mark: |
| Viewport is specified using the meta viewport tag            | Passed :heavy_check_mark: |
| Viewport is not defined to a fixed width                     | Passed :heavy_check_mark: |
| Content is sized to viewport                                 | Passed :heavy_check_mark: |
| Font size is large enough for easy reading on a small screen | Passed :heavy_check_mark: |
| Touch elements are not too close to each other               | Passed :heavy_check_mark: |

### Elastic Beanstalk

| Environment                        | Health                |
| ---------------------------------- | --------------------- |
| hollowverse-release-manager-master | :heavy_check_mark: OK |
| hollowverse-beta                   | :heavy_check_mark: OK |
| hollowverse-master                 | :heavy_check_mark: OK |
| hollowverse-new-app                | :heavy_check_mark: OK |
| hollowverse-api-master             | :heavy_check_mark: OK |
