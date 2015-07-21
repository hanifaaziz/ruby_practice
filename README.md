# ruby_practice
my_name = "hanifa"
my_age = 20
female = true
height = 1.58
weight = 45
uni = "queen mary" 
modules = ['OPP','PP','WD','L&DS']

my_name.capitalize!
bmi = weight/height/height

puts "My name is #{my_name}, I am #{my_age} years old."
puts "My weight is #{weight}, my height is #{height} and my BMI is #{bmi}"

if bmi >= 20
print "Your bmi is healthy"
else 
print "You are underweight"
end

modules.each do |module|
print #{module} 
end


