### dbcan-kit: CAZymes annotation using dbCAN
<br>


#### 1. Get Start

We shuffle the input protein dataset, split it into multiple chuncks, then use hmmscan to submit parallel jobs.

dbCAN v2: https://bcb.unl.edu/dbCAN2/download/


#### 2. Get Start

```
git clone https://github.com/jameslz/dbcan-kit
perl dbcan-kit/dbcan-kit  -t 40  -e 1e-15 -c 0.35 -d  /biostack/database/dbcan  dbcan-kit/examples/EscheriaColiK12MG1655.faa  EscheriaColiK12MG1655
```