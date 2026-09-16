# ⏱️ Temporizador HTML


Temporizador desenvolvido em HTML, CSS e JavaScript puro, focado em produtividade, gestão de tempo e uso rápido tanto em desktop quanto em dispositivos móveis. Destinado a quem fica/trabalha com o navegador aberto permanentemente.

![Temporizador](https://github.com/yoshiomaeda/Temporizador/blob/main/temporizadorV09.png)

## ✨ Funcionalidades

### 🎯 Controle de tempo

- Contagem regressiva em tempo real.
- Botões de duração pré-definida configuráveis.
- Início automático ao selecionar uma duração.
- Suporte a duração personalizada.
- Pausa, retomada, parada e reinicialização.

### ⚡ Ajustes rápidos durante a execução

Permite alterar o tempo restante sem interromper o temporizador:

- `-5m`
- `-1m`
- `+1m`
- `+5m`

### 📊 Indicadores visuais

- Exibição do tempo restante.
- Exibição do tempo decorrido.
- Barra de progresso dinâmica.
- Percentual restante.
- Alteração automática de cores conforme o tempo diminui:
  - 🟢 Verde
  - 🟠 Laranja
  - 🔴 Vermelho

### 🕒 Previsão de término

Exibe automaticamente o horário previsto para conclusão da atividade.

### 🔔 Alertas

- Alarme sonoro ao término.
- Notificação do navegador.
- Destaque visual da aba quando o tempo se esgota.

### 🏷️ Identificação da atividade

Permite definir um nome para o temporizador.

Exemplos:

- Estudo
- Reunião
- Pausa
- Atendimento
- Treinamento

O nome também é exibido nas notificações e no histórico.

### 📑 Histórico

Cada execução concluída registra:

| Campo | Descrição |
|---------|---------|
| Nome | Nome da atividade |
| Início | Horário de início |
| Término | Horário de término |
| Duração | Tempo utilizado |

### 🕘 Tempos recentes

Os últimos tempos utilizados são disponibilizados automaticamente em botões de acesso rápido.

Exemplo:

```text
15 min | 3 min | 30 min | 1 min
```

Ao clicar em um dos botões:

- A duração é selecionada automaticamente.
- A contagem é iniciada imediatamente.

### 💾 Persistência local

As informações são armazenadas no navegador utilizando **Local Storage**:

- Nome da atividade.
- Última duração selecionada.
- Configuração personalizada.
- Histórico de execuções.

### 📱 Interface responsiva

Compatível com:

- Desktop
- Tablets
- Smartphones

## ⚙️ Personalização

Os tempos padrão podem ser alterados facilmente editando o array:

```javascript
const OPCOES_TEMPO_MINUTOS = [3, 6, 9, 12, 15, 30, 45, 60];
```

Exemplo:

```javascript
const OPCOES_TEMPO_MINUTOS = [1, 5, 10, 15, 20, 25, 30, 60];
```

## 🛠 Tecnologias utilizadas

- HTML5
- CSS3
- JavaScript (Vanilla JS)
- Web Audio API
- Web Notifications API
- Local Storage

## 🚀 Como utilizar

1. Abra o arquivo `Temporizador.html` no navegador.
2. Informe um nome para a atividade (opcional).
3. Selecione uma duração.
4. O temporizador iniciará automaticamente.
5. Ajuste o tempo quando necessário.
6. Receba alerta sonoro e notificação ao término.

## 📄 Licença

Este projeto pode ser utilizado, modificado e distribuído livremente conforme a licença adotada pelo repositório.
