task :hello do
    puts "hello"
end

task :gen do
    puts "generate pdf..."
    `platex *.tex`
    `dvipdfmx *.dvi`
end

task :open do
    `open *.pdf`
end

task :clean do
    `rm *.dvi *.log *.nav *.out *.pdf *.snm 2>/dev/null`
end
