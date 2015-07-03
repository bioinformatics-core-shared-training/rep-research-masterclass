presentation: tools_for_reproducibility.html

example: example_main.html

clean:
	rm -rf example_main_cache example_main_files generated sample_logfile.txt

tools_for_reproducibility.html: tools_for_reproducibility.Rmd
	Rscript -e 'rmarkdown::render("tools_for_reproducibility.Rmd")'
	
example_main.html: example_main.Rmd
	Rscript -e 'rmarkdown::render("example_main.Rmd")'
