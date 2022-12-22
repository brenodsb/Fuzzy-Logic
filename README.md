# Fuzzy Logic
 Trabalho sobre Lógica Fuzzy em IA para definir consumo de combustível segundo os seguintes parâmetros:

        **Entrada (antecedentes):**

        Velocidade

        * Universo (intervalo de valores nítidos/crisp): 0km/h a 200km/h

        * Conjunto difuso (valores difusos): baixa, media, alta

        Marcha

        * Universo (intervalo de valores nítidos/crisp): 1ª a 5ª

        * Conjunto difuso (valores difusos): baixa, media, alta

        Inclinação do Terreno

        * Universo (intervalo de valores nítidos/crisp): 0% a 100%

        * Conjunto difuso (valores difusos): baixa, media, alta

        **Saída (consequentes):**

        Consumo de Combustivel

        * Universo (valores nítidos/crisp): 0 a 100%

        * Conjunto difuso (valores difusos): baixo, médio, alto

        **Regras de Decisão**

        * **SE** a inclinação foi alta **E** a marcha alta **OU**

        a velocidade foi baixa **E** a marcha foi baixa **E** a inclinacao foi baixa
        
        **ENTÃO** o consumo deve ser baixo

        * **SE** a velocidade foi media **OU** a velocidade foi alta **E**

        a marcha foi alta **OU** a inclinacao foi media
        
        **ENTÃO** o consumo deve ser media

        * **SE** a velocidade foi baixa **OU** a velocidade foi media **E**

        a inclinação foi alta **E** a marcha foi baixa
        
        **ENTÃO** o consumo deve ser alto