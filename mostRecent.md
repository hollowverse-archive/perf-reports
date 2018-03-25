# Report for tests performed on 2018-03-25

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

### [WebPageTest](http://www.webpagetest.org/results.php?test=180325_CX_e196071b27fe0ea2ac4db84dd54aff63)

| Test                       | First View | Repeat View |
| -------------------------- | ---------- | ----------- |
| Number of requests         | 85         | 33          |
| Time to first byte         | 1.67s      | 1.72s       |
| Fully loaded               | 11.29s     | 12.80s      |
| Response size              | 1193.32KiB | 232.21KiB   |
| Response size (compressed) | 841.77KiB  | 222.42KiB   |

### Lighthouse via WebPageTest

| Test                     | First View | Repeat View |
| ------------------------ | ---------- | ----------- |
| Performance              | 43%        | 43%         |
| First Meaningful Paint   | 4.87s      | 4.87s       |
| First Interactive        | 11.27s     | 11.27s      |
| Consistently Interactive | 11.27s     | 11.27s      |
| Speed Index Metric       | 8859       | 8859        |
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

### [WebPageTest](http://www.webpagetest.org/results.php?test=180325_E0_d5480c5c2a52209aeb47a233a688ef93)

| Test                       | First View | Repeat View |
| -------------------------- | ---------- | ----------- |
| Number of requests         | 16         | 2           |
| Time to first byte         | 1.58s      | 1.73s       |
| Fully loaded               | 4.92s      | 1.80s       |
| Response size              | 205.38KiB  | 8.08KiB     |
| Response size (compressed) | 169.16KiB  | 7.75KiB     |

### Lighthouse via WebPageTest

| Test                     | First View | Repeat View |
| ------------------------ | ---------- | ----------- |
| Performance              | 79%        | 79%         |
| First Meaningful Paint   | 2.78s      | 2.78s       |
| First Interactive        | 5.32s      | 5.32s       |
| Consistently Interactive | 5.32s      | 5.32s       |
| Speed Index Metric       | 3131       | 3131        |
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
