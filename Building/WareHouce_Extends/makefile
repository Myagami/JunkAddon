MAKEOBJ:= makeobj_51
SRCDIR:= ./
PAKDIR:= ./pak/

#png
$(PAKDIR)building_mod_1_ex.pak: $(SRCDIR)building_mod_1_ex.png $(SRCDIR)building.mh-cs-building_ex1.dat
	makeobj_51 pak $(PAKDIR)building_mod_1_ex.pak $(SRCDIR)building.mh-cs-building_ex1.dat
$(PAKDIR)building_mod_2_ex.pak: $(SRCDIR)building_mod_2_ex.png $(SRCDIR)building.mh-cs-building_ex2.dat
	makeobj_51 pak $(PAKDIR)building_mod_2_ex.pak $(SRCDIR)building.mh-cs-building_ex2.dat
$(PAKDIR)building_mod_3_ex.pak: $(SRCDIR)building_mod_3_ex.png $(SRCDIR)building.mh-cs-building_ex3.dat
	makeobj_51 pak $(PAKDIR)building_mod_3_ex.pak $(SRCDIR)building.mh-cs-building_ex3.dat
$(PAKDIR)building_mod_4_ex.pak: $(SRCDIR)building_mod_4_ex.png $(SRCDIR)building.mh-cs-building_ex4.dat
	makeobj_51 pak $(PAKDIR)building_mod_4_ex.pak $(SRCDIR)building.mh-cs-building_ex4.dat
$(PAKDIR)building_mod_5_ex.pak: $(SRCDIR)building_mod_5_ex.png $(SRCDIR)building.mh-cs-building_ex5.dat
	makeobj_51 pak $(PAKDIR)building_mod_5_ex.pak $(SRCDIR)building.mh-cs-building_ex5.dat
$(PAKDIR)building_mod_6_ex.pak: $(SRCDIR)building_mod_6_ex.png $(SRCDIR)building.mh-cs-building_ex6.dat
	makeobj_51 pak $(PAKDIR)building_mod_6_ex.pak $(SRCDIR)building.mh-cs-building_ex6.dat

.PHONY: clean
clean:
	rm -f pak/*.pak

.PHONY: all
all: $(PAKDIR)building_mod_1_ex.pak $(PAKDIR)building_mod_2_ex.pak $(PAKDIR)building_mod_3_ex.pak $(PAKDIR)building_mod_4_ex.pak $(PAKDIR)building_mod_5_ex.pak $(PAKDIR)building_mod_6_ex.pak
