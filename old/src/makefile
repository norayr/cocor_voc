#.ONESHELL

all:
		cd build && voc -s ../CRS.Mod \
		../CRT.Mod \
		../CRX.Mod \
		../CRA.Mod \
		../CRP.Mod \
		../Coco.Mod -m

test:
		cp ../EBNF/EBNF.atg build/
		cp *.FRM build
		cd build && ./Coco EBNF.atg
		cd build && voc -s EBNFS.Mod


clean:
		cd build && rm *
