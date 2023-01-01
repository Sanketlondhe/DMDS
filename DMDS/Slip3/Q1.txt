n = as.integer(readline(prompt = "Enter a Number :"))
rev = 0
while(n > 0){
  r = n%%10
  rev=rev * 10 + r
  n = n%/%10
}
print(paste("reverse no is :", rev)) 


while (n > 0) {
  r = n %% 10
  s = s + r
  n = n %/% 10
}
print(paste("Sum of the digits is :", s))