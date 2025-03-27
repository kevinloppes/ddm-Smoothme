### Backup e Recuperação  
- **Backup Completo**: Diário às 02:00 (AWS S3).  
- **Backup Incremental**: A cada 4 horas.  
- **Retenção**: 30 dias para backups completos, 7 dias para incrementais.  
- **Recuperação**:  
  1. Restaurar backup completo mais recente.  
  2. Aplicar backups incrementais sequenciais.  
  3. Validar integridade dos dados.  
- **Ferramentas**: AWS Backup, MySQL Workbench.  