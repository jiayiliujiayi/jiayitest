## scripts: run ssGSEA using Betsy
betsy_run.py --network_png ssgsea.pdf --num_cores 23 \\\
--input SignalFile --input_file counts.txt \\\
--dattr SignalFile.preprocess=count \\\
--output ssGSEAResults --output_file out-ssgsea \\\
--mattr geneset_file=.gmt

alternative:
--mattr geneset_database=hallmarks
--mattr geneset_database2=curated