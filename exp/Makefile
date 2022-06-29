top_dir=..

all:
	letce2 \
		lxc \
		build \
		$(top_dir)/node.cfg.d/ltu.cfg \
		$(top_dir)/node.cfg.d/mmwave.cfg \
		experiment.cfg

	emanegentransportxml -v nem-*/platform.xml
	
clean:
	letce2 lxc clean
