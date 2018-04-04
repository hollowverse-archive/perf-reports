# Report for tests performed on 2018-04-04

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

### [WebPageTest](http://www.webpagetest.org/results.php?test=180404_8W_5c6713526330fee9be96f9b7c30e9b97)

| Test                       | First View | Repeat View |
| -------------------------- | ---------- | ----------- |
| Number of requests         | 77         | 34          |
| Time to first byte         | 1.59s      | 1.70s       |
| Fully loaded               | 14.03s     | 16.05s      |
| Response size              | 1184.91KiB | 256.65KiB   |
| Response size (compressed) | 842.43KiB  | 229.93KiB   |

### Lighthouse via WebPageTest

| Test                     | First View | Repeat View |
| ------------------------ | ---------- | ----------- |
| Performance              | 38%        | 38%         |
| First Meaningful Paint   | 5.59s      | 5.59s       |
| First Interactive        | 12.32s     | 12.32s      |
| Consistently Interactive | 12.32s     | 12.32s      |
| Speed Index Metric       | 9697       | 9697        |
| Estimated Input Latency  | 0.03s      | 0.03s       |
| PWA                      | 45%        | 45%         |
| Accessibility            | 92%        | 92%         |
| Best Practices           | 81%        | 81%         |
| SEO                      | 89%        | 89%         |

## https://hollowverse.com/Tom_Hanks

### Security Headers

| URL                               | Grade |
| --------------------------------- | ----- |
| https://hollowverse.com/Tom_Hanks | N/A   |

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

### [WebPageTest](http://www.webpagetest.org/results.php?test=180404_RV_afab0535a48f0295d5f8cc0a56c74792)

| Test                       | First View | Repeat View |
| -------------------------- | ---------- | ----------- |
| Number of requests         | 16         | 2           |
| Time to first byte         | 1.61s      | 1.76s       |
| Fully loaded               | 6.89s      | 4.29s       |
| Response size              | 208.21KiB  | 8.09KiB     |
| Response size (compressed) | 169.42KiB  | 7.77KiB     |

### Lighthouse via WebPageTest

| Test                     | First View | Repeat View |
| ------------------------ | ---------- | ----------- |
| Performance              | 84%        | 84%         |
| First Meaningful Paint   | 2.48s      | 2.48s       |
| First Interactive        | 4.69s      | 4.69s       |
| Consistently Interactive | 4.69s      | 4.69s       |
| Speed Index Metric       | 2780       | 2780        |
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
| track-performance-production-reportPerformance | 0                                                   |
| process-image-production-processImage          | 0                                                   |
| assignEnvironment                              | 0                                                   |
| process-image-development-processImage         | 0                                                   |
