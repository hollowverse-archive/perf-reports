# Report for tests performed on 2018-04-10

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

### [WebPageTest](http://www.webpagetest.org/results.php?test=180410_HA_4f3fea816f3bb8b222e574a42ab26ef5)

| Test                       | First View | Repeat View |
| -------------------------- | ---------- | ----------- |
| Number of requests         | 75         | 31          |
| Time to first byte         | 1.58s      | 1.73s       |
| Fully loaded               | 16.15s     | 12.12s      |
| Response size              | 1182.33KiB | 234.05KiB   |
| Response size (compressed) | 840.29KiB  | 227.96KiB   |

### Lighthouse via WebPageTest

| Test                     | First View | Repeat View |
| ------------------------ | ---------- | ----------- |
| Performance              | 30%        | 30%         |
| First Meaningful Paint   | 6.57s      | 6.57s       |
| First Interactive        | 14.89s     | 14.89s      |
| Consistently Interactive | 14.89s     | 14.89s      |
| Speed Index Metric       | 11247      | 11247       |
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

### [WebPageTest](http://www.webpagetest.org/results.php?test=180410_DJ_2841ca2d7ca7b85f9beedbae4e072f40)

| Test                       | First View | Repeat View |
| -------------------------- | ---------- | ----------- |
| Number of requests         | 16         | 2           |
| Time to first byte         | 1.50s      | 1.54s       |
| Fully loaded               | 5.95s      | 3.99s       |
| Response size              | 212.94KiB  | 8.12KiB     |
| Response size (compressed) | 174.15KiB  | 7.80KiB     |

### Lighthouse via WebPageTest

| Test                     | First View | Repeat View |
| ------------------------ | ---------- | ----------- |
| Performance              | 86%        | 86%         |
| First Meaningful Paint   | 2.38s      | 2.38s       |
| First Interactive        | 4.39s      | 4.39s       |
| Consistently Interactive | 4.39s      | 4.39s       |
| Speed Index Metric       | 2678       | 2678        |
| Estimated Input Latency  | 0.03s      | 0.03s       |
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
| website-development-serveSsrMarkup             | 0                                                   |
| process-image-development-processImage         | 0                                                   |
