# PIS
BMSTU LABS
_____
Для генерации отчета:
- Изменить метадату в ноутбуке.    
Edit -> Edit notebook Metadata
- Из папки с ноутбуком выполнить:  
`jupyter nbconvert --to pdf --template=../../common/template.tplx <labFileName>.ipynb --output-dir=../../Reports`
