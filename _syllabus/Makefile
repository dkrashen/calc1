
all: syllabus schedule

syllabus: syllabus.tex
	pdflatex syllabus
	pdflatex syllabus
	rm syllabus.log syllabus.out syllabus.aux
	mv syllabus.pdf ..

schedule: lecture_schedule.tex
	pdflatex lecture_schedule
	pdflatex lecture_schedule
	rm lecture_schedule.log lecture_schedule.out lecture_schedule.aux
