# Benchmark
_NOTE: all results are evaluated from retrained model here._

## SISR (Single-Image Super-Resolution) 

|Model   |Scale Factor | Set5       | Set14      | BSD100     | Urban100   |
|:-------|:------------|:-----------|:-----------|:-----------|:-----------|
|Bicubic |     x2      |33.66/0.9299|30.24/0.8688|29.56/0.8431|26.88/0.8403|
|--------|-------------|------------|------------|------------|------------|
|Bicubic |     x4      |28.42/0.8104|26.00/0.7027|25.96/0.6675|23.14/0.6577|

## Image Denoise
|Model   | AWGN Level | BSD68      | Set12      | Urban100   |
|:-------|:-----------|:-----------|:-----------|:-----------|
|BM3D    |     15     |31.08/0.8722|32.37/0.8952|32.35/0.9220|
|--------|------------|------------|------------|------------|
|BM3D    |     25     |28.57/0.8013|29.97/0.8504|29.70/0.8777|
|--------|------------|------------|------------|------------|
|BM3D    |     50     |25.62/0.6864|26.72/0.7676|25.95/0.7791|

## Degradation Image Super-Resolution
|Model   | Scale | AWGN Level | Set5       | Set14      | Urban100   |
|:-------|:------|:-----------|:-----------|:-----------|:-----------|
|VDSR    |  x4   |     15     |26.14/0.7425|24.09/0.6320|22.10/0.6353|
|VDSR    |  x4   |     25     |24.66/0.6909|23.08/0.5866|21.27/0.5900|
|VDSR    |  x4   |     50     |22.20/0.5982|21.25/0.5092|19.74/0.5028|