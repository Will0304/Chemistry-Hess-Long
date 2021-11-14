import itertools
import re

c = ['2CO(g) + O2(g) -> 2CO2(g)','CO(g) + H2O(g) -> CO2(g) + H2(g)',
	 'CO(g) + H2(g) + O2(g) -> CO2(g) + H2O(g)','CH4(g) + 2O2(g) -> CO2(g) + 2H2O(g)',
	 'C(s) + 2H2(g) -> CH4(g)','2C(s) + O2(g) -> 2CO(g)','C(s) + H2O(g) -> CO(g) + H2(g)',
	 '2H2(g) + O2(g) -> 2H2O(g)']
n = 0
for i,(a,b,c) in enumerate(itertools.combinations(c,3)):
	if re.match(r'(?=.*CH4)(?=.*H2\(g\))(?=.*CO\(g\))(?=.*H2O\(g\))',a+b+c) :
		n+=1
		print(n,a,b,c,'\n',sep='\n')
