
This is a dual-agent project developed for dynamic prediction of postoperative delirium before and during surgery.
Agent.zip contains three files: PODPre.py constructs a preoperative POD risk prediction model based on preoperative static baseline features, outputting preoperative baseline risk probability; PODIntra.py integrates intraoperative temporal signals with the preoperative static features of Pre-Agent to achieve dynamic updating of intraoperative risks; and mian.py unifies the management system lifecycle.
models.zip contains two trained Agents
The division of the dataset is included in data.zip.
experiment.zip contains different experiments for DAPIP, including baseline model comparison, ablation studies, external validation, subgroup analysis, and more.
