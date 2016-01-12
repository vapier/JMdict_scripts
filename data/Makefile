SUBDIRS = KANJIDIC2 JMdict tagainijisho

all:
	$(foreach subdir, $(SUBDIRS), $(MAKE) -C $(subdir) all;)

clean:
	$(foreach subdir, $(SUBDIRS), $(MAKE) -C $(subdir) clean;)
