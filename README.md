# Repostório de personalização de graficos no matlab

Formatação de parametro de título

legenda1=['Espalhamento do feixe com variação da velocide do ar média de ' num2str(velocidade) 'm/s '];
texto_temp=['Variancia de ' ...
      '{\color{red}'...
    num2str(variancia_matlab,'%e') ' mm }'];
[t,s] = title(legenda1,...
    texto_temp,'Color','Black');
t.FontSize = 16;
legenda2=['Disperção do feixe na temperatura média de ' num2str(round(temperatura_media)) '°C '];
legend(legenda2,'Location','northwest');
