TARGETS=soccer symmetry visual_tracking walk motion_player my_walk

.PHONY: $(TARGETS)

release debug profile clean:
	@+for X in $(TARGETS); do \
	  echo make $@ $$X; \
	  make -s -C $$X $@ ; \
	done
