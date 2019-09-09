TEMPFILE := $(shell mktemp -u)

all: ldap_replication.png seed_cluster.png

%.png : %.dot
	dot -Tpng $< -o $@

clean:
	rm *.png
