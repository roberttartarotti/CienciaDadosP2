Os dados raw, que na verdade são external, não puderam ser carregados no projeto devido a falta de licença, para a coleta de dados diretamente do git, foi usado o seguinte procedimento em python no notebook:

github = "https://raw.githubusercontent.com/santanche/lab2learn/master/data/synthea/scenario02/csv"
allergies = pd.read_csv(os.path.join(github, "allergies.csv"))
careplans = pd.read_csv(os.path.join(github, "careplans.csv"))
conditions = pd.read_csv(os.path.join(github, "conditions.csv"))
devices = pd.read_csv(os.path.join(github, "devices.csv"))
encounter = pd.read_csv(os.path.join(github, "encounters.csv"))
immunications = pd.read_csv(os.path.join(github, "immunizations.csv"))
medications = pd.read_csv(os.path.join(github, "medications.csv"))
observations = pd.read_csv(os.path.join(github, "observations.csv"))
patient = pd.read_csv(os.path.join(github, "patients.csv"))
procedure = pd.read_csv(os.path.join(github, "procedures.csv"))

A origem dos dados é do seguinte repositorio:

https://github.com/santanche/lab2learn

Ou, mais especificamente:

https://github.com/santanche/lab2learn/tree/master/data/synthea

Para o cenário 3, os dados foram coletados de https://drive.google.com/drive/u/1/folders/1057xNQ373dZwvASZcX4PFzzHaspeZd8g
