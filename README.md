## Título: "Estudo de caso: Como uma empresa de tecnologia de bem-estar pode agir com inteligência?"
### Autor: "Bruno Marinho"
#### Data: "05-09-2023"

## **Cenário**

Você é um analista de dados júnior que trabalha na equipe de analistas de marketing da Bellabeat, uma fabricante de produtos de alta tecnologia voltados à saúde para mulheres. A Bellabeat é uma pequena empresa de sucesso, mas tem potencial para adquirir maior participação no mercado global de dispositivos inteligentes.

Urška Sršen, cofundadora e CEO da Bellabeat, acredita que a análise de dados de condicionamento físico a partir de dispositivos inteligentes pode ajudar a abrir novas oportunidades de crescimento para a empresa. Foi solicitado que você se concentre em um dos produtos da Bellabeat e analise dados de dispositivos inteligentes para obter informações sobre como os consumidores estão usando esses dispositivos. Os insights que você descobrir ajudarão a orientar a estratégia de marketing da empresa. Você apresentará sua análise à equipe executiva da Bellabeat juntamente com suas recomendações de alto nível para a estratégia de marketing da empresa.

### **Personagens e Produtos**
#### **Personagens**
* **Urška Sršen**: Confudadora e CEO da Bellabeat.
* **Sando Mur**: Matemático e confudador da Bellabeat; membro-chave da equipe executiva da Bellabeat.
* **Equipe de análise de marketing da Bellabeat**: Uma equipe de analistas de dados responsável por coletar, analisar e relatar dados que ajudam a orientar a estratégia de marketing da Bellabeat. Você se juntou a esta equipe há seis meses e tem estado ocupado aprendendo sobre a missão e os objetivos de negócios da Bellabeat – e como você, como analista de dados júnior, também pode ajudar a Bellabeat a alcançá-los.

#### **Produtos**
* **Aplicativo Bellabeat**: O aplicativo Bellabeat fornece aos usuários dados de saúde relacionados à sua atividade, sono, estresse, ciclo menstrual e hábitos de atenção plena. Esses dados podem ajudar os usuários a entender melhor seus hábitos atuais e tomar decisões saudáveis. O aplicativo Bellabeat se conecta à sua linha de produtos inteligentes de bem-estar.
* **Leaf**: O rastreador de bem-estar clássico da BellaBeat pode ser usado como pulseira, colar ou clipe. O rastreador Leaf se conecta ao aplicativo Bellabeat para rastrear a atividade, o sono e o estresse.
* **Time**: Este relógio de bem-estar combina a aparência atemporal de um relógio clássico com tecnologia inteligente para rastrear a atividade, o sono e o estresse do usuário. O relógio Time se conecta ao aplicativo Bellabeat para fornecer informações sobre seu bem-estar diário.
* **Spring**: Esta é uma garrafa de água que rastreia a ingestão diária de água por meio de tecnologia inteligente para garantir que você esteja adequadamente hidratado ao longo do dia. A garrafa Spring se conecta ao aplicativo BellaBeat para rastrear seus níveis de hidratação.
* **Planos da Bellabeat**: A Bellabeat também oferece aos usuários diferentes planos de assinatura. As assinaturas oferecem aos usuários acesso 24 horas por dia, 7 dias por semana, orientação totalmente personalizada sobre nutrição, atividade, sono, saúde e beleza, além de atenção plena com base em seu estilo de vida e objetivos.

### **Sobre a empresa**

Urška Sršen e Sando Mur fundaram a Bellabeat, uma empresa de alta tecnologia que fabrica produtos inteligentes focados na saúde. A Urška aproveitou sua experiência como artista para desenvolver uma tecnologia elegantemente projetada que informa e inspira mulheres em todo o mundo. A coleta de dados sobre atividade, sono, estresse e saúde reprodutiva permitiu à Bellabeat capacitar as mulheres com conhecimento sobre sua própria saúde e hábitos. Desde que foi fundada em 2013, a Bellabeat cresceu rapidamente e não levou muito tempo para se posicionar como uma empresa de bem-estar voltada à tecnologia para mulheres.

Em 2016, a Bellabeat abriu escritórios ao redor do mundo e lançou vários produtos. Os produtos Bellabeat tornaram-se disponíveis por meio de um número crescente de varejistas online, além de seu próprio canal de comércio eletrônico em [seu site](https://bellabeat.com/). A empresa investiu em mídia de publicidade tradicional, como rádio, outdoors, mídia impressa e televisão, mas se concentra amplamente no marketing digital. A Bellabeat investe o ano todo na Pesquisa do Google, mantendo páginas ativas no Facebook e Instagram, além de engajar os consumidores de forma consistente no Twitter. Além disso, a Bellabeat exibe anúncios em vídeo no Youtube e anúncios gráficos na rede de display do Google para apoiar campanhas em datas importantes de marketing.

A Urška sabe que uma análise dos dados de consumo disponíveis da Bellabeat revelaria mais oportunidades de crescimento. Ela pediu à equipe de análise de marketing para se concentrar em um produto da Bellabeat e analisar os dados de uso de dispositivos inteligentes para obter informações sobre como as pessoas já estão usando seus dispositivos inteligentes. Assim, por meio dessas informações, ela gostaria de conferir excelentes recomendações sobre como essas tendências podem nortear a estratégia de marketing da Bellabeat.

## **Etapas do processo de análise de dados**
##### **Perguntar**
##### **Preparar**
##### **Processar**
##### **Analisar**
##### **Compartilhar**
##### **Agir**

### **1 - Perguntar**

A tarefa de negócios concentra-se em analisar dados de consumidores que usam dispositivos inteligentes que não são da Bellabeat, no intuito de encontrar tendências de uso por parte dessas pessoas. A partir disso, será analisado como podem ser aplicadas essas tendências em clientes de um produto da Bellabeat e como essas tendências podem direcionar futuras campanhas de marketing da empresa.

As partes interessadas para essa tarefa de negócios são a cofundadora e CEO Urška Sršen, o cofundador e membro-chave da equipe executiva da Bellabeat Sando Mur e a equipe de análise de marketing da empresa.

Tanto Urška Sršen como Sando Mur são as partes interessadas primárias, por fazerem parte do time responsável pela tomada de decisões da empresa. Já a equipe de análise de marketing corresponde à parte interessada secundária.

### **2 - Preparar**

Para a análise deste estudo de caso, serão utilizados dados públicos (licença CC0) do rastreador de condicionamento físico FitBit, [disponíveis na plataforma Kaggle](https://www.kaggle.com/arashnic/fitbit).

O conjunto de dados contém números de um rastreador de condicionamento físico pessoal do Fitbit de 33 usuários. Esses usuários consentiram com o envio dos dados pessoais do rastreador, incluindo os resultados a cada minuto de atividade física, frequência cardíaca e monitoramento do sono, monotirados entre os dias 12/04/2016 e 12/05/2016. São apresentadas informações sobre atividades diárias, passos e frequência cardíaca.

O conjunto de dados está dividido em 18 arquivos .csv, todos eles no formato longo. Cada dado monitorado pelos dispositivos inteligentes (atividade física, frequência cardíaca e monitoramento do sono) está disposto diferentes intervalos de tempo: por minuto, por hora e por dia, separados por arquivo. Ou seja, há o arquivo .csv para o monitoramento de atividade por minuto, monitoramento de atividade por hora, monitoramento de atividade por dia, monitoramento do sono por minuto e assim sucessivamente.

A credibilidade de qualquer dado presente no conjunto pode ser atestada pela abordagem chamada ROCCC, onde:

* **R**eliable, ou seja, real ou confiável;

* **O**riginal, ou seja, a originalidade do dado;

* **C**omprehensive, ou seja, que os dados sejam abrangentes;

* **C**urrent, ou seja, que os dados sejam atuais; e

* **C**ited, ou seja, que sejam citados ou utilizados por outras pessoas.

Para confirmar que os dados em questão são confiáveis e originais, basta saber que eles foram colhidos em consentimento dos entrevistados de uma pesquisa via Amazon Mechanical Turk.

Para atestar que são abrangentes, basta perceber que existem dados a cada minuto, hora e dia.

O quarto ponto, a atualidade dos dados, é o mais difícil de atestar, pois estamos em 2023. No entanto, como serão usados apenas para um estudo de caso, esse fator pode ser desconsiderado, ou melhor, os dados de 2016 podem ser considerados como atuais.

Para atestar que estão sendo citados ou utilizados por outras pessoas, na plataforma Kaggle é informado que esse conjunto de dados já foi baixado 99.567 vezes, além de ter sido visto por 520.128 pessoas (números referentes a 23/08/2023).

Por fim, a própria plataforma Kaggle classifica esse conjunto de dados com nota 10 em 'usabilidade', obtendo avaliação máxima nos critérios completude, credibilidade e compatibilidade.

### **3 - Processar**

Na primeira parte da fase de processar os dados será utilizado o programa Microsoft Excel para limpar os dados antes de carregá-los na IDE RStudio, que será utilizada junto da linguagem de programação R para analisar os dados.

A opção por R se deu devido ao fato de ser uma linguagem de programação voltada para a análise e visualização de dados e pela facilidade de trabalhar com um grande conjunto de dados.

O primeiro passo é escolher quais conjuntos de dados utilizar. Após análise inicial, foram escolhidos três arquivos .csv para o prosseguimento deste estudo de caso: os arquivos de nome 'dailyActivity_merged', 'minuteMETsNarrow_merged' e 'sleepDay_merged'.

O primeiro deles, que vai ser identificado neste estudo de caso como 'Atividades por dia' acumula os registros de atividades diários de cada usuário, trazendo informações como total de passos, distância percorrida, calorias gastas ou até mesmo tempo de inatividade.

Já o segundo, que será identificado como 'METs por minuto', traz a métrica METs, que é a unidade utilizada para quantificar a intensidade da atividade física realizada e compara com o quanto de calorias o corpo gastaria caso estivesse em repouso. Por exemplo, se uma atividade contabiliza 5 METs, significa dizer que essa pessoa está gastando 5 vezes mais calorias que gastaria caso estivesse em repouso.

Por último, o 'Registro sono', traz as informações de tempo dormindo e na cama de cada usuário participante da pesquisa de 24 dos 33 participantes da entrevista do conjunto de dados.

##### **Limpeza**

A seguir, será iniciado o processo de limpeza dos três data frames, para excluir informações desnecessárias ou faltantes dos conjuntos de dados para que não atrapalhem durante a análise.

Em primeiro, será analisado o conjunto de dados de 'Atividades por dia'. Analisando as colunas, é possível perceber que existe duas colunas, a TotalDistance (distância total) e TrackerDistance (distância do rastreador) que medem a distância percorrida pelo usuário e valor que o reastreador registrou.

A princípio os números parecem ser iguais para todos os usuários, mas ao utilizar a função de formatação condicional para confirmar se de fato os dados são iguais, foi possível perceber que o usuário de Id 7007744171 registrou valores diferentes entre as colunas. Apenas ele apresentou essa anomalia e precisou ficar de observação especial para as analises futuras.

Na sequência foi verificado se existem dados duplicados na planilha. Ao executar a função de remover duplicadas do Excel, nenhum dado duplicado foi encontrado.

Os demais dados na planilha serão úteis para análise, portanto, será feita a verificação e limpeza do próximo conjunto de dados, 'METs por dia'.

Novamente foi verificado se existem valores duplicados na planilha, que não foram encontrados. Como esse conjunto de dados possui três informações principais (id, data e MET), não foi necessário realizar nenhum processo de exclusão. Vale salientar que para o momento de análise em si, esses dados podem ser agrupados por vários critérios, como por hora (já que estão exibidos em minutos), MET máximo, mínimo ou média.

O terceiro conjunto de dados, o de 'Registro sono', também não apresentou dados duplicados. Mais uma vez, como todos os dados presentes nesse arquivo serão úteis para a análise. nenhuma informação foi excluída.

Após isso, já no RStudio, o primeiro passo será carregar os pacotes que serão usados em R para analisar e visualizar os dados. Neste caso, será instalado o pacote Tidyverse, que na verdade é uma coleção de pacotes de R desenvolvida especialmente para se trabalhar com dados.

```{r, message=FALSE}
library(tidyverse)
library(here)
library(skimr)
library(janitor)
```

Na sequência, serão carregados os dados:

```{r}
atividades_por_dia <- read.csv("C:/Workspace R/Fitabase Data 4.12.16-5.12.16/dailyActivity_merged.csv", sep=",")

mets_por_minuto <- read.csv("C:/Workspace R/Fitabase Data 4.12.16-5.12.16/minuteMETsNarrow_merged.csv", sep=",")

registro_sono <-   read.csv("C:/Workspace R/Fitabase Data 4.12.16-5.12.16/sleepDay_merged.csv", sep=",")
```

Ainda em R é dada continuação ao processo de limpeza. Utilizando a função glimpse em cada um dos conjuntos de dados, foi possível verificar que a coluna de data está configurada como string (chr). Para melhor trabalhar com datas, os valores serão convertidos para data nos três conjuntos de dados.

```{r }
glimpse(atividades_por_dia)
glimpse(mets_por_minuto)
glimpse(registro_sono)
```

Com isso, foi alterado em todos os três conjuntos de dados.

```{r }
atividades_por_dia <- atividades_por_dia %>%
  rename(Date = ActivityDate) %>%
  mutate(Date = as_date(Date, format = "%m/%d/%Y"))

atividades_por_dia <- atividades_por_dia %>% 
  mutate(Date = weekdays(as.Date(Date, "%m/%d/%Y")))
atividades_por_dia$Date <- factor(atividades_por_dia$Date, levels= c("domingo","segunda-feira", "terça-feira", "quarta-feira", "quinta-feira","sexta-feira", "sábado"))

mets_por_minuto <- mets_por_minuto %>%
  mutate(ActivityMinute = as.POSIXct(ActivityMinute,format ="%m/%d/%Y %I:%M:%S %p" , tz=Sys.timezone()))

registro_sono <- registro_sono %>%
  mutate(SleepDay = as.POSIXct(SleepDay,format ="%m/%d/%Y %I:%M:%S %p" , tz=Sys.timezone()))
```

Utilizando novamente a função glimpse para verificar que os tipos de dados foram alterados.

```{r }
glimpse(atividades_por_dia)
glimpse(mets_por_minuto)
glimpse(registro_sono)
```

Além disso, foi criado um novo data frame com as informações de METs por minuto, desta vez fazendo a média de quantos METs cada usuário somou.

```{r }
mets_agrupado <- mets_por_minuto %>%
  group_by(Id) %>%
  summarize(mean_METs = mean(METs))
```

```{r }
head(mets_agrupado)
```

### **4 - Analisar**

#### **4.1 Médias de atividades**

Após preparar e processar os dados, é dado início à etapa de análise. Um dos insights foi feito ao computar a média de passos gastos e tempo médio de atividades leves, moderadas, intensas e sem atividades, assim como o gasto calórico de cada um dos usuários.

```{r }
media_atividades <- atividades_por_dia %>%
  group_by(Id) %>% 
  drop_na() %>% 
  summarize(mean_total_steps = mean(TotalSteps),
            mean_total_distance = mean(TotalDistance),
            mean_very_active_minutes = mean(VeryActiveMinutes),
            mean_fairly_active_minutes = mean(FairlyActiveMinutes),
            mean_lightly_active_minutes = mean(LightlyActiveMinutes),
            mean_sedentary_active_minutes = mean(SedentaryMinutes),
            mean_calories = mean(Calories))

media_sono <- registro_sono %>%
  group_by(Id) %>%
  drop_na() %>%
  summarize(mean_sleep_time = mean(TotalMinutesAsleep),
            mean_bed_time = mean(TotalTimeInBed))

resumo_atividades <- atividades_por_dia %>%
  select(TotalSteps,
         VeryActiveMinutes, 
         FairlyActiveMinutes, 
         LightlyActiveMinutes, 
         SedentaryMinutes, 
         Calories) %>%
  summary()

resumo_sono <- registro_sono %>%
  select(TotalMinutesAsleep,
         TotalTimeInBed) %>%
  summary()
```

O resumo das atividades mostra que a média diária de minutos foi:

Atividades intensas = 21m 09s;
Atividades moderadas = 13m 33s;
Atividades leves = 192m 48s (ou 3h 12m 48s);
Sem atividade = 991m 12s (ou 16h 31m 12s);
Média de calorias gastas = 2304 calorias;
Média de passos dados = 7638  passos dados. 
Média diária de minutos dormidos = 419m 30s (ou 6h 59m 30s);
Média diária de tempo na cama = 458m 36s (ou 7h 38m 36s).

A primeira conclusão que pode ser observada a partir desse tratamento nos dados é que as pessoas não têm o hábito de realizar atividades físicas intensas, o que fica demonstrado no tempo médio de atividades intensas e moderadas se comparado com o de atividades leves ou até mesmo sem atividade.

Do outro lado, naturalmente, usuários que têm maior tempo médio de atividades intensas obtiveram o maior consumo de calorias.

```{r, fig.keep = "none"}
ggplot(data=media_atividades)+
  geom_smooth(mapping=aes(x=mean_very_active_minutes, y=mean_calories), se=FALSE)

ggplot(data=media_atividades)+
  geom_smooth(mapping=aes(x=mean_lightly_active_minutes, y=mean_calories), se=FALSE)

ggplot(data=media_atividades)+
  geom_smooth(mapping=aes(x=mean_fairly_active_minutes, y=mean_calories),  se=FALSE)

ggplot(data=media_atividades)+
  geom_smooth(mapping=aes(x=mean_sedentary_active_minutes, y=mean_calories),  se=FALSE)
```

#### **4.2 Proporção de passos dados com calorias gastas**

Outra observação compravada é que, quanto mais passos o usuário dá, mais calorias ele gasta.

```{r, fig.keep = "none"}
ggplot(data=media_atividades)+
  geom_smooth(mapping=aes(x=mean_total_steps, y=mean_calories)) +
  geom_point(mapping=aes(x=mean_total_steps, y=mean_calories))
```

#### **4.3 Proporção de passos dados com distância percorrida**

Naturalmente, quanto mais passos o usuário dá, ele também tende a ter uma maior distância percorrida.

```{r, fig.keep = "none"}
ggplot(data=media_atividades)+
  geom_smooth(mapping=aes(x=mean_total_steps, y=mean_total_distance))+
  geom_point(mapping=aes(x=mean_total_steps, y=mean_total_distance))
```

#### **4.4 Proporção de tempo de cama com tempo de atividade e calorias gastas**

Unindo os conjuntos de dados que trazem os tempos médios de atividade e de sono, será possível trazer mais constatações para a análise. Para isso, é usada a função merge.

```{r, fig.keep = "none"}
media_atividades_e_sono_unificado <- merge(media_atividades, media_sono)
```

Uma dessas constatações é que usuários que registraram maior tempo de cama, tiveram menos tempo de atividades, e consequentemente, menos calorias gastas.

```{r, fig.keep = "none"}
ggplot(data=media_atividades_e_sono_unificado)+
  geom_smooth(mapping=aes(x=mean_calories, y=mean_bed_time))+
  geom_point(mapping=aes(x=mean_calories, y=mean_bed_time))

ggplot(data=media_atividades_e_sono_unificado)+
  geom_smooth(mapping=aes(x=mean_sedentary_active_minutes, y=mean_bed_time))
```

#### **4.5 Uso de METs**

Essas constatações foram reafirmadas quando comparados os METs dos usuários. Para relembrar, MET é a unidade utilizada para quantificar a intensidade da atividade física realizada, comparando com o quanto de calorias o corpo gastaria caso estivesse em repouso. Novamente, é possível ver como quem teve maior quantidade de METs foi quem teve um maior gasto calórico e maior distância percorrida durante as atividades.

Para isso, foram adicionados os dados de MET ao conjunto de dados unificado de médias de atividades e sono.

```{r, fig.keep = "none"}
media_atividades_sono_mets_unificado <- 
  merge(media_atividades_e_sono_unificado, mets_agrupado)

ggplot(data=media_atividades_sono_mets_unificado)+
  geom_smooth(mapping=aes(x=mean_METs, y=mean_bed_time))

ggplot(data=media_atividades_sono_mets_unificado)+
  geom_smooth(mapping=aes(x=mean_METs, y=mean_total_distance))
```

#### **4.6 Dias da semana com maior registro de atividades**

Também foi possível fazer um recorte por dias da semana e decifrar quais foram os dias com maior distância percorrida e/ou passos dados pelos usuários em suas atividades registrados.

```{r, fig.keep = "none"}
ggplot(data=atividades_por_dia, aes(x=Date, y=TotalSteps)) +
  geom_bar(stat="identity")+
  theme(axis.text.x = element_text(angle = 30))

ggplot(data=atividades_por_dia, aes(x=Date, y=TotalDistance)) +
  geom_bar(stat="identity")+
  theme(axis.text.x = element_text(angle = 30))
```

### **5 - Compartilhar**

#### **5.1 Médias de atividades**

Como dito anteriormente, a primeira constatação foi que as pessoas não têm o hábito de realizar atividades físicas intensas, o que fica demonstrado no tempo médio de atividades intensas e moderadas se comparado com o de atividades leves ou até mesmo sem atividade, conforme os números abaixo:

Atividades intensas = 21m 09s;
Atividades moderadas = 13m 33s;
Atividades leves = 192m 48s (ou 3h 12m 48s);
Sem atividade = 991m 12s (ou 16h 31m 12s);
Média de calorias gastas = 2304 calorias;
Média de passos dados = 7638  passos dados. 
Média diária de minutos dormidos = 419m 30s (ou 6h 59m 30s);
Média diária de tempo na cama = 458m 36s (ou 7h 38m 36s).

Naturalmente, usuários que têm maior tempo médio de atividades intensas obtiveram o maior consumo de calorias.

![](https://github.com/brunohmds/estudo_de_caso_google_bellabeat/blob/main/grafico_atividades_intensas_calorias.png)

![](https://github.com/brunohmds/estudo_de_caso_google_bellabeat/blob/main/grafico_atividades_moderadas_calorias.png)

![](https://github.com/brunohmds/estudo_de_caso_google_bellabeat/blob/main/grafico_atividades_leves_calorias.png)

![](https://github.com/brunohmds/estudo_de_caso_google_bellabeat/blob/main/grafico_sem_atividades_calorias.png)

#### **5.2 Proporção de passos dados com calorias gastas**

A tabela a seguir demonstra que quanto mais passos o usuário dá, mais calorias ele gasta.

![](https://github.com/brunohmds/estudo_de_caso_google_bellabeat/blob/main/grafico_passos_dados_calorias.png)

#### **5.3 Proporção de passos dados com distância percorrida**

A tabela a seguir mostra que quanto mais passos o usuário dá, ele tende a ter uma maior distância percorrida.

![](https://github.com/brunohmds/estudo_de_caso_google_bellabeat/blob/main/grafico_passos_dados_distancia_percorrida.png)

#### **5.4 Proporção de tempo de cama com tempo de atividade e calorias gastas**

Os dados apontam que usuários que registraram maior tempo de cama, tiveram menos tempo de atividades e menos calorias gastas.

![](https://github.com/brunohmds/estudo_de_caso_google_bellabeat/blob/main/grafico_tempo_cama_sem_atividades.png)

![](https://github.com/brunohmds/estudo_de_caso_google_bellabeat/blob/main/grafico_tempo_cama_calorias.png)

#### **5.5 Uso de METs**

Gráfico mostra que usuários que tiveram maior gasto calórico e maior distância percorrida durante as atividades registraram uma maior quantidade de METs.

![](https://github.com/brunohmds/estudo_de_caso_google_bellabeat/blob/main/grafico_mets_tempo_cama.png)

![](https://github.com/brunohmds/estudo_de_caso_google_bellabeat/blob/main/grafico_mets_distancia_percorrida.png)

#### **5.6 Dias da semana com maior registro de atividades**

Os dois gráficos a seguir mostram a distância percorrida e os passos percorridos por dia da semana.

![](https://github.com/brunohmds/estudo_de_caso_google_bellabeat/blob/main/grafico_total_passos_dia_semana.png)

![](https://github.com/brunohmds/estudo_de_caso_google_bellabeat/blob/main/grafico_distancia_percorrida_dia_semana.png)

### **6 - Agir**

Atividade física é primordial para que o ser humano tenha uma melhor qualidade de vida. Pensando nisso, as sugestões a seguir foram tomadas com base nos dados analisados e com um objetivo principal: incentivar que os usuários da Bellabeat continuem usando seus produtos.

Uma das sugestões é incentivar o usuário a fazer as atividades logado no aplicativo da empresa. Conforme os dados mostram, praticamente nenhum usuário faz as atividadaes logado. Para combater esse número baixo, a empresa pode criar uma espécie de rede social fitness, onde os usuários logados, podem fazer comparativos com amigos de qualquer métrica que é medida nos dispositivos da Bellabeat, como calorias gastas ou maior tempo de atividades. 

A segunda sugestão diz respeito ao incentivo próprio do usuário em continuar praticando exercícios físicos. Estipular a função de metas pessoais pode ser uma forma de incentivo. O usuário poderia estipular metas como quantos dias da semana quer praticar atividades (o que contribuiria para aumentar os números de atividades em dias menos ativos, como domingos e segundas-feiras, como mostram os dados); tempo mínimo de atividades intensas; total de calorias gastas, entre outros. Essas metas podem ser diárias, semanais ou mensais, assim o usuário pode pensar no longo prazo e manter uma constância nas suas atividades, atrelando essa sugestão com a primeira.

Outra sugestão é fazer um programa de fidelidade, onde o usuário, ao atingir determinada meta proposta pela empresa, pode acumular pontos dentro do aplicativo para posteriormente trocar por produtos Bellabeat.
