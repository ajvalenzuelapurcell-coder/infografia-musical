[infografia.html](https://github.com/user-attachments/files/22256562/infografia.html)
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Producción Musical en Chile: La Brecha Entre Estudiar y Trabajar</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;700;900&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
        }
        .chart-container {
            position: relative;
            width: 100%;
            max-width: 500px;
            margin-left: auto;
            margin-right: auto;
            height: 300px;
            max-height: 350px;
        }
        @media (min-width: 768px) {
            .chart-container {
                height: 350px;
                max-height: 400px;
            }
        }
    </style>
</head>
<body class="bg-[#00A0B0]">
    <div class="container mx-auto p-4 md:p-8">

        <header class="text-center mb-12">
            <h1 class="text-4xl md:text-5xl font-extrabold text-white leading-tight">La Brecha Silenciosa</h1>
            <p class="text-xl md:text-2xl text-white mt-2 max-w-4xl mx-auto">El shock de realidad para los productores musicales egresados en Chile.</p>
        </header>

        <main class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">

            <div class="md:col-span-2 lg:col-span-3 bg-white/10 p-6 rounded-lg text-white">
                <h2 class="text-2xl font-bold mb-2 text-[#EDC951]">Introducción: El Sueño vs. La Realidad</h2>
                <p class="text-base">Estudiar producción musical en Chile es el primer paso de un sueño para miles de jóvenes. Sin embargo, al egresar, muchos se enfrentan a una industria cuyas demandas y dinámicas difieren enormemente de lo aprendido en el aula. Esta infografía explora las deficiencias académicas clave y el posterior "choque con la realidad" laboral, identificando las habilidades que realmente definen el éxito en el campo.</p>
            </div>

            <div class="bg-white rounded-lg shadow-2xl p-6 flex flex-col">
                <h3 class="text-xl font-bold text-[#6A4A3C] mb-2">Foco Académico: Teoría vs. Práctica</h3>
                <p class="text-gray-600 text-sm mb-4">Las mallas curriculares a menudo priorizan los conocimientos teóricos sobre la experiencia práctica y tangible. Los estudiantes egresan con una base conceptual sólida, pero con una notoria falta de horas de estudio aplicando esas habilidades en proyectos reales y simulaciones de trabajo profesional.</p>
                <div class="chart-container flex-grow">
                    <canvas id="theoryPracticeChart"></canvas>
                </div>
            </div>

            <div class="bg-white rounded-lg shadow-2xl p-6 flex flex-col">
                <h3 class="text-xl font-bold text-[#6A4A3C] mb-2">Carencia de Habilidades de Negocio</h3>
                <p class="text-gray-600 text-sm mb-4">La formación técnica es solo una parte de la ecuación. Habilidades cruciales para la autogestión y la sostenibilidad económica, como el marketing, la negociación y la gestión de derechos, son consistentemente subestimadas en los programas académicos.</p>
                <div class="chart-container flex-grow">
                    <canvas id="businessSkillsChart"></canvas>
                </div>
            </div>

            <div class="bg-white rounded-lg shadow-2xl p-6 flex flex-col">
                <h3 class="text-xl font-bold text-[#6A4A3C] mb-2">El Espejismo del Trabajo Estable</h3>
                <p class="text-gray-600 text-sm mb-4">La expectativa de un contrato de tiempo completo en un estudio de grabación es una rareza. La realidad del productor musical moderno es la de un profesional independiente, donde la capacidad de autogestión y la búsqueda proactiva de proyectos son la norma del día a día.</p>
                 <div class="chart-container flex-grow">
                    <canvas id="workTypeChart"></canvas>
                </div>
            </div>
            
            <div class="md:col-span-2 lg:col-span-3 bg-white rounded-lg shadow-2xl p-6">
                <h3 class="text-xl font-bold text-[#6A4A3C] mb-2 text-center">Perfil del Egresado vs. Demanda Real de la Industria</h3>
                <p class="text-gray-600 text-sm mb-4 text-center max-w-3xl mx-auto">Existe una clara desconexión entre las habilidades que se refuerzan en la academia y las que la industria valora para contratar y, más importante, para volver a contratar. Mientras el egresado promedio domina la técnica, el mercado busca profesionales integrales con altas capacidades de comunicación, gestión y networking.</p>
                <div class="chart-container mx-auto" style="max-width: 600px;">
                    <canvas id="skillsRadarChart"></canvas>
                </div>
            </div>
            
            <div class="md:col-span-2 lg:col-span-3 bg-white rounded-lg shadow-2xl p-6">
                <h3 class="text-2xl font-bold text-[#6A4A3C] mb-4 text-center">El Camino Hacia el Éxito Sostenible</h3>
                <p class="text-gray-600 text-sm mb-6 text-center">Para prosperar, el productor musical debe evolucionar de un técnico a un emprendedor creativo. Esto implica construir sobre la base técnica un conjunto de habilidades de negocio y emocionales que permitan navegar la complejidad del mercado.</p>
                
                <div class="flex flex-col md:flex-row items-center justify-center space-y-4 md:space-y-0 md:space-x-4">
                    <div class="text-center p-4 border-2 border-[#EB6841] rounded-lg w-full md:w-1/4">
                        <div class="text-4xl mb-2">🎵</div>
                        <h4 class="font-bold text-[#EB6841]">Fundamento Técnico</h4>
                        <p class="text-xs text-gray-600">Dominio de software, mezcla, mastering, teoría musical.</p>
                    </div>
                    <div class="text-2xl font-bold text-[#CC333F] transform md:rotate-0 rotate-90">&rarr;</div>
                    <div class="text-center p-4 border-2 border-[#CC333F] rounded-lg w-full md:w-1/4">
                        <div class="text-4xl mb-2">📈</div>
                        <h4 class="font-bold text-[#CC333F]">Habilidades de Negocio</h4>
                        <p class="text-xs text-gray-600">Marketing, finanzas, gestión de proyectos, derechos de autor.</p>
                    </div>
                    <div class="text-2xl font-bold text-[#EDC951] transform md:rotate-0 rotate-90">&rarr;</div>
                    <div class="text-center p-4 border-2 border-[#EDC951] rounded-lg w-full md:w-1/4">
                        <div class="text-4xl mb-2">🤝</div>
                        <h4 class="font-bold text-[#EDC951]">Inteligencia Emocional</h4>
                        <p class="text-xs text-gray-600">Comunicación, networking, gestión de clientes, resiliencia.</p>
                    </div>
                </div>
            </div>

        </main>
    </div>

    <script>
        document.addEventListener('DOMContentLoaded', () => {
            const wrapLabel = (label, maxLength = 16) => {
                if (label.length <= maxLength) {
                    return label;
                }
                const words = label.split(' ');
                const lines = [];
                let currentLine = '';
                words.forEach(word => {
                    if ((currentLine + word).length > maxLength) {
                        lines.push(currentLine.trim());
                        currentLine = '';
                    }
                    currentLine += word + ' ';
                });
                lines.push(currentLine.trim());
                return lines;
            };

            const tooltipTitleCallback = (tooltipItems) => {
                const item = tooltipItems[0];
                let label = item.chart.data.labels[item.dataIndex];
                if (Array.isArray(label)) {
                    return label.join(' ');
                } else {
                    return label;
                }
            };
            
            const sharedChartOptions = {
                responsive: true,
                maintainAspectRatio: false,
                plugins: {
                    legend: {
                        labels: {
                            color: '#6A4A3C',
                            font: {
                                family: "'Inter', sans-serif"
                            }
                        }
                    },
                    tooltip: {
                        callbacks: {
                            title: tooltipTitleCallback
                        }
                    }
                }
            };

            const theoryPracticeCtx = document.getElementById('theoryPracticeChart').getContext('2d');
            new Chart(theoryPracticeCtx, {
                type: 'doughnut',
                data: {
                    labels: ['Foco Teórico', 'Práctica Aplicada'],
                    datasets: [{
                        label: 'Distribución Curricular',
                        data: [70, 30],
                        backgroundColor: ['#EB6841', '#EDC951'],
                        borderColor: '#FFFFFF',
                        borderWidth: 4
                    }]
                },
                options: {
                    ...sharedChartOptions,
                    plugins: {
                        ...sharedChartOptions.plugins,
                        title: { display: false }
                    }
                }
            });

            const businessSkillsCtx = document.getElementById('businessSkillsChart').getContext('2d');
            new Chart(businessSkillsCtx, {
                type: 'bar',
                data: {
                    labels: ['Marketing y Autopromoción', 'Gestión de Derechos y Royalties', 'Negociación y Contratos', 'Finanzas para Freelancers'].map(l => wrapLabel(l)),
                    datasets: [{
                        label: 'Nivel de Carencia Reportado',
                        data: [90, 85, 80, 75],
                        backgroundColor: '#CC333F',
                        borderColor: '#CC333F',
                        borderWidth: 1
                    }]
                },
                options: {
                    ...sharedChartOptions,
                    indexAxis: 'y',
                    scales: {
                        x: {
                            ticks: { color: '#6A4A3C' },
                            grid: { display: false }
                        },
                        y: {
                            ticks: { color: '#6A4A3C' },
                             grid: { display: false }
                        }
                    },
                    plugins: {
                        legend: { display: false }
                    }
                }
            });
            
            const workTypeCtx = document.getElementById('workTypeChart').getContext('2d');
            new Chart(workTypeCtx, {
                type: 'pie',
                data: {
                    labels: ['Trabajo Freelance / Por Proyecto', 'Contrato Estable'],
                    datasets: [{
                        label: 'Modalidad de Trabajo',
                        data: [85, 15],
                        backgroundColor: ['#00A0B0', '#EB6841'],
                        borderColor: '#FFFFFF',
                        borderWidth: 4
                    }]
                },
                options: { ...sharedChartOptions }
            });

            const skillsRadarCtx = document.getElementById('skillsRadarChart').getContext('2d');
            new Chart(skillsRadarCtx, {
                type: 'radar',
                data: {
                    labels: ['Técnica (Mezcla/Master)', 'Teoría Musical', 'Comunicación Asertiva', 'Gestión de Proyectos', 'Networking Efectivo', 'Marketing Personal'],
                    datasets: [
                        {
                            label: 'Perfil del Egresado',
                            data: [9, 8, 4, 3, 3, 2],
                            fill: true,
                            backgroundColor: 'rgba(235, 104, 65, 0.2)',
                            borderColor: '#EB6841',
                            pointBackgroundColor: '#EB6841',
                            pointBorderColor: '#fff',
                            pointHoverBackgroundColor: '#fff',
                            pointHoverBorderColor: '#EB6841'
                        },
                        {
                            label: 'Perfil Demandado por la Industria',
                            data: [7, 6, 9, 9, 8, 7],
                            fill: true,
                            backgroundColor: 'rgba(204, 51, 63, 0.2)',
                            borderColor: '#CC333F',
                            pointBackgroundColor: '#CC333F',
                            pointBorderColor: '#fff',
                            pointHoverBackgroundColor: '#fff',
                            pointHoverBorderColor: '#CC333F'
                        }
                    ]
                },
                options: {
                    ...sharedChartOptions,
                    scales: {
                        r: {
                            angleLines: { color: 'rgba(106, 74, 60, 0.2)' },
                            grid: { color: 'rgba(106, 74, 60, 0.2)' },
                            pointLabels: {
                                color: '#6A4A3C',
                                font: {
                                    size: 10,
                                    family: "'Inter', sans-serif"
                                }
                            },
                            ticks: {
                                color: '#6A4A3C',
                                backdropColor: 'rgba(255, 255, 255, 0.75)',
                                stepSize: 2
                            },
                            suggestedMin: 0,
                            suggestedMax: 10
                        }
                    }
                }
            });
        });
    </script>
</body>
</html>
