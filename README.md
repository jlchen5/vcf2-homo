# vcf2-homo

提取GT为0/0，1/1或2/2的行

~~~
zcat file.vcf.gz  |awk '$10 ~ /^0\/0/ || $10 ~ /^1\/1/ || $10 ~ /^2\/2/' > file_Hom.vcf

~~~
