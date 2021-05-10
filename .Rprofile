# REMEMBER to restart R after you modify and save this file!

if (file.exists("~/.Rprofile")) {
  base::sys.source("~/.Rprofile", envir = environment())
}
options(
  blogdown.serve_site.startup = FALSE,
  blogdown.knit.on_save = TRUE,
  blogdown.new_bundle = TRUE,
  blogdown.author = "Peter Baumgartner",
  blogdown.ext = ".Rmd", # '.Rmd', '.Rmarkdown' or '.md'
  # whenever changing method: delete files from previous knit and restart!
  blogdown.method = 'html', # 'html' (default), 'markdown' or 'custom'
  blogdown.subdir = "post",
  blogdown.yaml.empty	= TRUE	# Preserve empty fields in YAML?
)


# fix Hugo version
options(blogdown.hugo.version = "0.82.0")