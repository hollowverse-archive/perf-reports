# Report for tests performed on 2018-04-01

## https://hollowverse.com

### Security Headers

| URL                     | Grade |
| ----------------------- | ----- |
| https://hollowverse.com | N/A   |

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

### [WebPageTest](http://www.webpagetest.org/results.php?test=180401_YQ_e19649f78f76f449a90750bd6f0ba508)

| Test                       | First View | Repeat View |
| -------------------------- | ---------- | ----------- |
| Number of requests         | 79         | 15          |
| Time to first byte         | 1.63s      | 1.55s       |
| Fully loaded               | 14.00s     | 7.27s       |
| Response size              | 1201.77KiB | 157.86KiB   |
| Response size (compressed) | 850.09KiB  | 151.47KiB   |

### Lighthouse via WebPageTest

| Test                     | First View | Repeat View |
| ------------------------ | ---------- | ----------- |
| Performance              | 41%        | 41%         |
| First Meaningful Paint   | 5.19s      | 5.19s       |
| First Interactive        | 11.62s     | 11.62s      |
| Consistently Interactive | 11.62s     | 11.62s      |
| Speed Index Metric       | 9198       | 9198        |
| Estimated Input Latency  | 0.04s      | 0.04s       |
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

### [WebPageTest](http://www.webpagetest.org/results.php?test=180401_K0_90ec3a4bb370ee30d604f61e51ea6eb9)

| Test                       | First View | Repeat View |
| -------------------------- | ---------- | ----------- |
| Number of requests         | 16         | 2           |
| Time to first byte         | 1.56s      | 1.62s       |
| Fully loaded               | 6.31s      | 4.09s       |
| Response size              | 205.67KiB  | 8.08KiB     |
| Response size (compressed) | 169.44KiB  | 7.75KiB     |

### Lighthouse via WebPageTest

| Test                     | First View | Repeat View |
| ------------------------ | ---------- | ----------- |
| Performance              | 80%        | 80%         |
| First Meaningful Paint   | 2.56s      | 2.56s       |
| First Interactive        | 5.41s      | 5.41s       |
| Consistently Interactive | 5.41s      | 5.41s       |
| Speed Index Metric       | 2919       | 2919        |
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
