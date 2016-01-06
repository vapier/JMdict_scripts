SUBDIRS = JMdict KANJIDIC2 tagainijisho

all:
	$(foreach subdir, $(SUBDIRS), $(MAKE) -C $(subdir) all;)

clean:
	$(foreach subdir, $(SUBDIRS), $(MAKE) -C $(subdir) clean;)
