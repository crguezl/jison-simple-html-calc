task :default => 'calculator.js'
file %q{calculator.js} do
  sh "jison calculator.jison calculator.l -o calculator.js"
end

task :postfix => 'postfix.js'
file %q{postfix.js} do
  sh "jison postfix.jison calculator.l -o postfix.js"
end
