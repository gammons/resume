desc "Generate PDF from markdown"
task :generate_pdf do
  `pandoc README.md -o resume.pdf`
end

task default: :generate_pdf
