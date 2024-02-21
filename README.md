# 2-desafio-cybersecurity
import pyaes
##abrir aquivo criptografado
file_nome = 'teste.txt.ransomwaretroll'
file = open(file_name, 'rb')
file_data = file.read()
file.close()

#chave de descriptografia
key = b'testeransomware'
aes = pyaes.AESModeOfOperationCTR(key)
descrypt)data = aes.decrypt*(file_data)

#remover o arquivo criptografado
os.remove(file_name)

#criar um novo arquivo descriptografado

new_file = 'teste.txt'
new_file.write(decrypt_data)
new_file.close()
