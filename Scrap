from lxml import html
import requests

page = requests.get('http://www.svet.rs/nas-svet/estrada/pevacica-zbunila-fanove-milica-pavlovic-pokazala-svoju-dvojnicu-foto')
tmpsrv = html.fromstring(page.content)

Bolidi = tmpsrv.xpath('//span[@class="k_author"]/text()')
Zbunjeni_bolidi = tmpsrv.xpath('//span[@class="k_noteLead"]/text()')

print 'Bolidi:', Bolidi
print 'Zbunjeni Bolidi:', Zbunjeni_bolidi
