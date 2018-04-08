# Report for tests performed on 2018-04-08

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

### [WebPageTest](http://www.webpagetest.org/results.php?test=180408_J6_b5055274a35f04c220241fde6dcb5a14)

| Test                       | First View | Repeat View |
| -------------------------- | ---------- | ----------- |
| Number of requests         | 75         | 15          |
| Time to first byte         | 1.71s      | 1.72s       |
| Fully loaded               | 13.98s     | 6.75s       |
| Response size              | 1181.68KiB | 143.79KiB   |
| Response size (compressed) | 839.63KiB  | 140.85KiB   |

### Lighthouse via WebPageTest

| Test                     | First View | Repeat View |
| ------------------------ | ---------- | ----------- |
| Performance              | 36%        | 36%         |
| First Meaningful Paint   | 5.77s      | 5.77s       |
| First Interactive        | 12.68s     | 12.68s      |
| Consistently Interactive | 12.68s     | 12.68s      |
| Speed Index Metric       | 10106      | 10106       |
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

### [WebPageTest](http://www.webpagetest.org/results.php?test=180408_12_e23f4d0f85ff6080a9597c92ab1889e4)

| Test                       | First View | Repeat View |
| -------------------------- | ---------- | ----------- |
| Number of requests         | 16         | 2           |
| Time to first byte         | 1.56s      | 1.56s       |
| Fully loaded               | 6.50s      | 4.02s       |
| Response size              | 212.77KiB  | 8.09KiB     |
| Response size (compressed) | 173.99KiB  | 7.76KiB     |

### Lighthouse via WebPageTest

| Test                     | First View | Repeat View |
| ------------------------ | ---------- | ----------- |
| Performance              | 82%        | 82%         |
| First Meaningful Paint   | 2.61s      | 2.61s       |
| First Interactive        | 4.85s      | 4.85s       |
| Consistently Interactive | 4.85s      | 4.85s       |
| Speed Index Metric       | 2909       | 2909        |
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
| website-development-development-serveSsrMarkup | 18                                                  |
| process-image-production-processImage          | 0                                                   |
| assignEnvironment                              | 0                                                   |
| process-image-development-processImage         | 0                                                   |
