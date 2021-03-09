# convers-ometros
conversão de metros em cm e mm
medida = float(input('digite uma distância em metros? '))
cm = medida * 100
mm = medida * 1000
print('a media de {}m corresponde a {:.0f}cm \ne {:.0f}mm '.format(medida, cm, mm))
