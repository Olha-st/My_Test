fin = open ( "input.txt" )
fout = open ( "output.txt", "w" )
while True:
  s = fin.readline()
  if not s: break
  age = int ( s.split()[1] )
  if age < 5:
    fout.write ( s )
fin.close()
fout.close()
