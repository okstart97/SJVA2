###### π‘ νμΌ λ€μ΄λ‘λ <br> ######
- GET <b>/file/path/to/download</b><br>
  Root νμλ§ κ°λ₯<br>
  <br>
- Parameter<br>
  apikey : APIKEY<br>
  <br>
- μ) https://localhost:9999/file/data/db/rclone.conf?apikey=0123456789<br>

###### π‘ λ²μ­ <br> ######
- GET <b>/system/api/trans/do</b><br>
  <br>
- Parameter<br>
  text : λ²μ­ν  λ¬Έμ<br>
  source : text λ¬Έμμ. μλ΅μ ja<br>
  target : λ²μ­ν  λ¬Έμμ. μλ΅μ ko<br>
  <br>
- Response<br>
  ret : success / fail / exception<br>
  data : μ€νκ²°κ³Ό / λΉμΉΈ / exception μ€λͺ<br>
  
###### π‘ νμΌ μλ‘λ <br> ######
- μ μμ μ νμΌ μ΄λμ΄ νμν  κ²½μ° μμμ λ°λ‘ SJVAλ‘ μλ‘λ<br>
    - curl -F 'file=@νμΌκ²½λ‘' http://SJVA URL/upload<br>
