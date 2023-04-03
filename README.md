# FastApiMiniDemo

Dejo por aquí los links de las demos de FastApi enseñadas en la reunión de core:

*Ejemplo básico* :
* https://git.lnst.es/corelabs/fastapiminidemo

*Ejemplo básico con seguridad* :
* https://git.lnst.es/corelabs/fastapisecurity

*Al descargar el proyecto, puede que pida instalar para que funcione* :
<pre>
pip install "fastapi[all]"

pip install "uvicorn[standard]"

pip install "python-jose[cryptography]"

pip install "passlib[bcrypt]"
</pre>


*Para arrancar el proyecto* :
* fastapiminidemo (main.py):
<pre>
uvicorn main:app --reload
</pre>

* fastapisecurity (main.py o mainjwt.py):
<pre>
uvicorn main:app --reload

o

uvicorn mainjwt:app --reload
</pre>

*Referencias* :

* https://fastapi.tiangolo.com/tutorial/

* https://fastapi.tiangolo.com/tutorial/security/

* https://fastapi.tiangolo.com/tutorial/security/first-steps/

* https://fastapi.tiangolo.com/tutorial/security/get-current-user/

* https://fastapi.tiangolo.com/tutorial/security/simple-oauth2/

* https://fastapi.tiangolo.com/tutorial/security/oauth2-jwt/


*Versión usada de python (3.11.2)*:

* https://www.python.org/downloads/release/python-3112/
