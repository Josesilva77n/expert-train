# expert-train> curl -X PUT \
  -H "Authorization: token {SEU_TOKEN}" \
  -H "Content-Type: application/json" \
  -d '{
    "message": "Adicionando novo arquivo",
    "content": "{BASE64_DO_CONTEÚDO_DO_ARQUIVO}",
    "branch": "main"
  }' \
  https://api.github.com/repos/{josesilva77n}/{expert-train}/contents/{desktop>aulagitsexta}
  
  
