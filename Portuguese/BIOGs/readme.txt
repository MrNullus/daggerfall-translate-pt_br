Colocar ficheiros BIOG*.txt de substituição nesta pasta.

O formato do nome é BIOG[class]T[index].txt
A classe é um valor entre 0 e 17, inclusive. Correspondem à mesma lista que o jogador escolhe quando inicia um novo personagem.
O índice é qualquer número. As biografias clássicas usam 0, e os mods são livres de usar qualquer outro número que queiram.

Por exemplo, BIOG10T2.txt seria uma biografia alternativa válida para um Ladrão, ou uma classe personalizada de Ladrão-adjacente.

Para permitir que os mods tenham um backstory personalizado para acompanhar a biografia, os ficheiros BIOG podem opcionalmente começar com a seguinte linha:

#12345

Isto fará com que o jogo utilize o ID de cordel especificado (aqui, 12345) para o texto de História encontrado na folha de caracteres. Por defeito, o id da cadeia de caracteres é 4116 + classe. As cordas clássicas param em 9999, pelo que os mods podem utilizar um ITextProvider personalizado para ter cordas personalizadas acima deste valor.

Note-se que o texto BIOG não está actualmente incluído nas tabelas centrais de cadeias de caracteres de localização.
É necessário copiar a versão linguística correcta dos ficheiros para a pasta BIOG.
Os ficheiros BIOG em inglês são utilizados por defeito, as versões DE e FR são também fornecidas por conveniência.

Os modelos T0 não são exactamente os ficheiros originais Arena2 BIOG. Foram feitas algumas correcções de bugs e pequenas alterações de equilíbrio.

Crédito para ficheiros corrigidos a Frank 'Deepfighter' Schwalb. Por favor ver "readme-deepfighter.txt" para mais informações.
