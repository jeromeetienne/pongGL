# just a little makefile to store repreatitive task

#################################################################################
#		ponggl								#
#################################################################################

build:
	zip -r ponggl.zip ponggl_src

build_crx:
	google-chrome --pack-extension=ponggl_src --pack-extension-key=$(HOME)/.chrome_extension_key.pem
	
clean:
	rm -rf ponggl.zip ponggl_src.crx
