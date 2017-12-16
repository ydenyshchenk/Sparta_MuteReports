# Sparta_MuteReports disables logging product views to `report_viewed_product_index ` table
## WARNINGS:
- It stops indexing product views and as result product views reports as such as 'most viewed products', 'recently viewed' stop to work as well
- using *Sparta_MuteReports* is on your own risk

## Installation
```
git clone git@github.com:ydenyshchenk/Sparta_MuteReports.git app/code/Sparta/MuteReports
bin/magento module:enable Sparta_MuteReports
bin/magento setup:upgrade
```

P.S. It's workaround for the issue like https://github.com/magento/magento2/issues/9300