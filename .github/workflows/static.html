<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Registro de Alumnos</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            height: 100vh;
        }
        .container {
            width: 50%;
            background-color: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        h2 {
            text-align: center;
        }
        form, .login-form {
            display: flex;
            flex-direction: column;
        }
        input {
            margin: 10px 0;
            padding: 10px;
            border-radius: 5px;
            border: 1px solid #ccc;
        }
        button {
            padding: 10px;
            border: none;
            border-radius: 5px;
            background-color: #28a745;
            color: white;
            cursor: pointer;
        }
        .alumno-list {
            margin-top: 20px;
        }
        .alumno-item {
            border-bottom: 1px solid #ccc;
            padding: 10px 0;
        }
        .hidden {
            display: none;
        }
    </style>
</head>
<body>

<div id="login-container" class="container">
    <h2>Login</h2>
    <form class="login-form" id="loginForm">
        <input type="text" id="username" placeholder="Usuario" required>
        <input type="password" id="password" placeholder="Contraseña" required>
        <button type="submit">Ingresar</button>
    </form>
    <p id="loginError" style="color: red;" class="hidden">Usuario o contraseña incorrectos</p>
</div>

<div id="register-container" class="container hidden">
    <h2>Registro de Alumnos</h2>
    <form id="registerForm">
        <input type="text" id="nombre" placeholder="Nombre" required>
        <input type="text" id="direccion" placeholder="Dirección" required>
        <input type="tel" id="telefono" placeholder="Teléfono" required>
        <input type="text" id="dni" placeholder="DNI" required>
        <button type="submit">Registrar Alumno</button>
    </form>
    <h3>Lista de Alumnos Registrados</h3>
    <div id="alumnoList" class="alumno-list"></div>
</div>

<script>
    // Usuario y contraseña predefinidos
    const validUsername = "admin";
    const validPassword = "admin123";

    // Seleccionamos los elementos
    const loginContainer = document.getElementById('login-container');
    const registerContainer = document.getElementById('register-container');
    const loginForm = document.getElementById('loginForm');
    const registerForm = document.getElementById('registerForm');
    const alumnoList = document.getElementById('alumnoList');
    const loginError = document.getElementById('loginError');

    // Array para almacenar los alumnos
    let alumnos = [];

    // Evento de Login
    loginForm.addEventListener('submit', function(e) {
        e.preventDefault();
        const username = document.getElementById('username').value;
        const password = document.getElementById('password').value;

        if (username === validUsername && password === validPassword) {
            loginContainer.classList.add('hidden');
            registerContainer.classList.remove('hidden');
        } else {
            loginError.classList.remove('hidden');
        }
    });

    // Evento de Registro de Alumno
    registerForm.addEventListener('submit', function(e) {
        e.preventDefault();

        const nombre = document.getElementById('nombre').value;
        const direccion = document.getElementById('direccion').value;
        const telefono = document.getElementById('telefono').value;
        const dni = document.getElementById('dni').value;

        const nuevoAlumno = {
            nombre,
            direccion,
            telefono,
            dni
        };

        alumnos.push(nuevoAlumno);
        actualizarLista();
        registerForm.reset();
    });

    // Función para actualizar la lista de alumnos
    function actualizarLista() {
        alumnoList.innerHTML = '';
        alumnos.forEach(alumno => {
            const alumnoItem = document.createElement('div');
            alumnoItem.classList.add('alumno-item');
            alumnoItem.textContent = `Nombre: ${alumno.nombre}, Dirección: ${alumno.direccion}, Teléfono: ${alumno.telefono}, DNI: ${alumno.dni}`;
            alumnoList.appendChild(alumnoItem);
        });
    }
</script>

</body>
</html>
