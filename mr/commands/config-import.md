# config:import
वर्तमान अनुप्रयोगावरील कॉन्फिगरेशन आयात करा.

**Usage:**
```
drupal config:import [options]
ci
```

## Available options
Option | Details
-------|-------------
--file | आयात करण्यासाठी कॉन्फिगरेशनच्या संग्रहण फाईलचा मार्ग.
--directory | आयात करण्यासाठी कॉन्फिगरेशनच्या निर्देशिकेत मार्ग.
--remove-files | सिंक्रोनाइझेशननंतर फायली काढा.

## Examples
* संरचना फाइल पुरवा.
```
drupal config:import \
  --file=/path/to/config/file
```
* संरचना निर्देशिका द्या.
```
drupal config:import  \
  --directory=/path/to/config/dir
```
