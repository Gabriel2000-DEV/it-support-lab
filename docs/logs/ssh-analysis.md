# Análise de Logs SSH

## Evento detectado
- Tentativas de brute force

## Comando utilizado
cat auth.log | grep "Failed password"

## Conclusão
IP suspeito realizando múltiplas tentativas

## Ação recomendada
- Bloquear IP via firewall
