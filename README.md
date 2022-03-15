# KJP-BC-Lab-3-
a = {     name : "shahzaib",
sectiom : "B",
subject : "science",
quiz : [25,52,60,85,26,75,56,65,89],
qutotal : 50,
assign : [60,55,14,48,36,22,78],
asstotal : 40,
midterm : 65,
final : 55,
} 
for (let i = 0; i &lt; a.quiz.length; i++)
for (let j = 0; j &lt; a.assign.length; j++)
if (a.quiz[1] >= a.qutotal && a.assign[j]>= a.asstotal)
console.log("pass")
else
console.log("fail") 
