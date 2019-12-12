betsy_run.py --network_png ssgsea.pdf --num_cores 23 \
--input SignalFile --input_file counts.txt \
--dattr SignalFile.preprocess=count \
--output ssGSEAResults --output_file out-ssgsea \
--mattr geneset_file=.gmt

alternative:
betsy_run.py --network_png ssgsea.pdf --num_cores 23 \
--input SignalFile --input_file counts.txt \
--dattr SignalFile.preprocess=count \
--output ssGSEAResults --output_file out-ssgsea \
--mattr geneset_database=hallmarks
--mattr geneset_database2=curated