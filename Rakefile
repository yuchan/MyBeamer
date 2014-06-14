src = "mybeamer"

task :gen do
    puts "generate pdf..."
    `platex #{src}.tex`
    `dvipdfmx #{src}.dvi`
end

task :open do
    `open #{src}.pdf`
end

task :clean do
    `rm #{src}.aux #{src}.toc #{src}.dvi #{src}.log #{src}.nav #{src}.out #{src}.pdf #{src}.snm 2>/dev/null`
end
