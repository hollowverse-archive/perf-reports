# Report for tests performed on 2018-04-03

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

### [WebPageTest](http://www.webpagetest.org/results.php?test=180403_GW_05071b01ad8389863f8522a66fdf2c68)

| Test                       | First View | Repeat View |
| -------------------------- | ---------- | ----------- |
| Number of requests         | 74         | 30          |
| Time to first byte         | 1.62s      | 1.85s       |
| Fully loaded               | 13.97s     | 11.38s      |
| Response size              | 1192.32KiB | 244.51KiB   |
| Response size (compressed) | 850.41KiB  | 238.88KiB   |

### Lighthouse via WebPageTest

| Test                     | First View | Repeat View |
| ------------------------ | ---------- | ----------- |
| Performance              | 42%        | 42%         |
| First Meaningful Paint   | 4.95s      | 4.95s       |
| First Interactive        | 11.70s     | 11.70s      |
| Consistently Interactive | 11.70s     | 11.70s      |
| Speed Index Metric       | 9141       | 9141        |
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

### [WebPageTest](http://www.webpagetest.org/results.php?test=180403_S3_5fbfbb430003dce124a46b3f9c7bb87c)

| Test                       | First View | Repeat View |
| -------------------------- | ---------- | ----------- |
| Number of requests         | 16         | 2           |
| Time to first byte         | 1.61s      | 1.63s       |
| Fully loaded               | 6.45s      | 3.30s       |
| Response size              | 208.20KiB  | 8.07KiB     |
| Response size (compressed) | 169.41KiB  | 7.75KiB     |

### Lighthouse via WebPageTest

| Test                     | First View | Repeat View |
| ------------------------ | ---------- | ----------- |
| Performance              | 85%        | 85%         |
| First Meaningful Paint   | 2.23s      | 2.23s       |
| First Interactive        | 4.70s      | 4.70s       |
| Consistently Interactive | 4.70s      | 4.70s       |
| Speed Index Metric       | 2588       | 2588        |
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
| track-performance-production-reportPerformance | 3                                                   |
| process-image-production-processImage          | 0                                                   |
| assignEnvironment                              | 0                                                   |
| process-image-development-processImage         | 0                                                   |
