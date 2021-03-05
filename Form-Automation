#created on 25 February 2021
from selenium import webdriver

Chrome = "C:\Program Files\chromedriver.exe"
driver = webdriver.Chrome(Chrome)

driver.get('https://forms.gle/czLbXU5455NpCCr76')

#Nama 
nama = 'Nama Saya'
n = driver.find_element_by_xpath('//*[@id="mG61Hd"]/div[2]/div/div[2]/div[1]/div/div/div[2]/div/div[1]/div/div[1]/input')
#No Absem
absen = '01'
a = driver.find_element_by_xpath('//*[@id="mG61Hd"]/div[2]/div/div[2]/div[2]/div/div/div[2]/div/div[1]/div/div[1]/input')
#Kelas
kelas = 'KELAS'
k = driver.find_element_by_xpath('//*[@id="mG61Hd"]/div[2]/div/div[2]/div[3]/div/div/div[2]/div/div[1]/div/div[1]/input')
#Submit
submit = driver.find_elements_by_xpath('//*[@id="mG61Hd"]/div[2]/div/div[3]/div[1]/div/div/span')

n.send_keys(nama)
a.send_keys(absen)
k.send_keys(kelas)
submit.click()
