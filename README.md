mkdir -p Macro-Mundial/{data/{raw,processed},backend/{database,etl,api},frontend/{dashboards,src},docs}
cd Macro-Mundial
touch README.md data/sources.md backend/requirements.txt
git add . && git commit -m "Estrutura inicial do projeto BI" && git push
