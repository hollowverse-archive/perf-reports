# Report for tests performed on 2018-04-02

## https://hollowverse.com

### Security Headers

| URL                     | Grade |
| ----------------------- | ----- |
| https://hollowverse.com | A     |

### Mobile Friendliness

| Test                                                         | Status                    |
| ------------------------------------------------------------ | ------------------------- |
| Is page mobile friendly?                                     | :heavy_check_mark: Yes    |
| Does not use plugins incompatible with mobile devices        | :heavy_check_mark: Passed |
| Viewport is specified using the meta viewport tag            | :heavy_check_mark: Passed |
| Viewport is not defined to a fixed width                     | :heavy_check_mark: Passed |
| Content is sized to viewport                                 | :heavy_check_mark: Passed |
| Font size is large enough for easy reading on a small screen | :heavy_check_mark: Passed |
| Touch elements are not too close to each other               | :heavy_check_mark: Passed |

### [WebPageTest](http://www.webpagetest.org/results.php?test=180402_AD_060d5149e340d4e238a9698a331babed)

| Test                       | First View | Repeat View |
| -------------------------- | ---------- | ----------- |
| Number of requests         | 97         | 14          |
| Time to first byte         | 1.67s      | 1.55s       |
| Fully loaded               | 22.13s     | 6.26s       |
| Response size              | 1294.86KiB | 156.13KiB   |
| Response size (compressed) | 940.55KiB  | 151.71KiB   |

### Lighthouse via WebPageTest

| Test                     | First View | Repeat View |
| ------------------------ | ---------- | ----------- |
| Performance              | 38%        | 38%         |
| First Meaningful Paint   | 5.15s      | 5.15s       |
| First Interactive        | 13.03s     | 13.03s      |
| Consistently Interactive | 13.03s     | 13.03s      |
| Speed Index Metric       | 9288       | 9288        |
| Estimated Input Latency  | 0.03s      | 0.03s       |
| PWA                      | 45%        | 45%         |
| Accessibility            | 92%        | 92%         |
| Best Practices           | 81%        | 81%         |
| SEO                      | 89%        | 89%         |

## https://hollowverse.com/Tom_Hanks

### Security Headers

| URL                               | Grade |
| --------------------------------- | ----- |
| https://hollowverse.com/Tom_Hanks | A     |

### Mobile Friendliness

| Test                                                         | Status                    |
| ------------------------------------------------------------ | ------------------------- |
| Is page mobile friendly?                                     | :heavy_check_mark: Yes    |
| Does not use plugins incompatible with mobile devices        | :heavy_check_mark: Passed |
| Viewport is specified using the meta viewport tag            | :heavy_check_mark: Passed |
| Viewport is not defined to a fixed width                     | :heavy_check_mark: Passed |
| Content is sized to viewport                                 | :heavy_check_mark: Passed |
| Font size is large enough for easy reading on a small screen | :heavy_check_mark: Passed |
| Touch elements are not too close to each other               | :heavy_check_mark: Passed |

### [WebPageTest](http://www.webpagetest.org/results.php?test=180402_B1_709dd28eec006336693fbe288a2eb683)

| Test                       | First View | Repeat View |
| -------------------------- | ---------- | ----------- |
| Number of requests         | 16         | 2           |
| Time to first byte         | 1.53s      | 1.79s       |
| Fully loaded               | 6.02s      | 3.46s       |
| Response size              | 208.77KiB  | 8.09KiB     |
| Response size (compressed) | 169.98KiB  | 7.76KiB     |

### Lighthouse via WebPageTest

| Test                     | First View | Repeat View |
| ------------------------ | ---------- | ----------- |
| Performance              | 87%        | 87%         |
| First Meaningful Paint   | 2.12s      | 2.12s       |
| First Interactive        | 4.60s      | 4.60s       |
| Consistently Interactive | 4.60s      | 4.60s       |
| Speed Index Metric       | 2453       | 2453        |
| Estimated Input Latency  | 0.02s      | 0.02s       |
| PWA                      | 55%        | 55%         |
| Accessibility            | 97%        | 97%         |
| Best Practices           | 94%        | 94%         |
| SEO                      | 90%        | 90%         |

## [Elastic Beanstalk Health](https://docs.aws.amazon.com/elasticbeanstalk/latest/dg/health-enhanced-status.html)

| Environment                        | Health                   |
| ---------------------------------- | ------------------------ |
| hollowverse-release-manager-master | :heavy_check_mark: Green |
| hollowverse-beta                   | :heavy_check_mark: Green |
| hollowverse-master                 | :heavy_check_mark: Green |
| hollowverse-new-app                | :heavy_check_mark: Green |
| hollowverse-api-master             | :heavy_check_mark: Green |

## AWS Lambda Health

| Function                                       | Number of Invocation Errors (for the past 24 hours) |
| ---------------------------------------------- | --------------------------------------------------- |
| track-performance-production-reportPerformance | 3                                                   |
| process-image-production-processImage          | 6                                                   |
| assignEnvironment                              | 0                                                   |
| process-image-development-processImage         | 15                                                  |
