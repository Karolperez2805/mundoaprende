let puntos = 0;

function mostrarCuestionario(id) {
    document.querySelectorAll('.cuestionario').forEach(cuestionario => {
        cuestionario.style.display = 'none';
    });
    document.getElementById(id).style.display = 'block';
}

function calcularPuntos(id) {
    const cuestionario = document.getElementById(id);
    const respuestas = cuestionario.querySelectorAll('input[type="radio"]:checked');
    let puntosGanados = 0;

    respuestas.forEach(respuesta => {
        puntosGanados += parseInt(respuesta.value);
    });

    puntos += puntosGanados;
    alert(Has ganado ${puntosGanados} puntos. Total de puntos: ${puntos});
}