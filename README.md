[!reporte html.txt](https://github.com/user-attachments/files/29111808/reporte.html.txt)
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Informe de Tiempos en Reuniones y Ceremonias</title>
    <style>
        body { font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; background-color: #f4f6f9; color: #333; margin: 0; padding: 20px; }
        .container { max-width: 1100px; margin: 0 auto; background: #fff; padding: 30px; border-radius: 8px; box-shadow: 0 4px 6px rgba(0,0,0,0.1); }
        h1 { color: #1a365d; border-bottom: 2px solid #3182ce; padding-bottom: 10px; margin-top: 0; }
        h2 { color: #2c5282; margin-top: 30px; border-bottom: 1px solid #e2e8f0; padding-bottom: 5px; }
        h3 { color: #4a5568; margin-top: 20px; font-size: 1.1em; }
        .iteration-info { background-color: #ebf8ff; border-left: 4px solid #3182ce; padding: 15px; margin-bottom: 25px; border-radius: 0 4px 4px 0; }
        .iteration-info p { margin: 5px 0; font-size: 1.1em; }
        table { width: 100%; border-collapse: collapse; margin-top: 10px; margin-bottom: 20px; background: #fff; }
        th { background-color: #2b6cb0; color: white; text-align: left; padding: 10px; font-size: 0.95em; }
        td { padding: 10px; border-bottom: 1px solid #e2e8f0; font-size: 0.9em; }
        tr:hover { background-color: #f7fafc; }
        .summary-box { display: flex; gap: 20px; margin-bottom: 25px; margin-top: 15px; }
        .card { flex: 1; background: #f7fafc; border: 1px solid #e2e8f0; border-radius: 6px; padding: 15px; text-align: center; }
        .card .number { font-size: 1.8em; font-weight: bold; color: #2b6cb0; margin-top: 5px; }
        .badge-reunion { background-color: #feebc8; color: #c05621; padding: 3px 8px; border-radius: 4px; font-size: 0.85em; font-weight: bold; }
        .badge-ceremonia { background-color: #e6fffa; color: #234e52; padding: 3px 8px; border-radius: 4px; font-size: 0.85em; font-weight: bold; }
        .user-block { background: #fff; border: 1px solid #e2e8f0; border-radius: 8px; padding: 20px; margin-bottom: 35px; box-shadow: 0 2px 4px rgba(0,0,0,0.05); }
    </style>
</head>
<body>
<div class="container">
    <h1>Informe de Inversión de Tiempo: Reuniones y Ceremonias</h1>
    <div class="iteration-info">
        <p><strong>Iteración:</strong> 15/06/2026 al 19/06/2026</p>
        <p><strong>Fuente de datos:</strong> SlackTime_1781813386085.xlsx</p>
    </div>

    <!-- Herson Garcia -->
    <div class="user-block">
        <h2>👤 Colaborador: Herson_Garcia@satrack.com</h2>
        <div class="summary-box">
            <div class="card">
                <div>Tiempo en Reuniones</div>
                <div class="number">5.50 hrs</div>
            </div>
            <div class="card">
                <div>Tiempo en Ceremonias</div>
                <div class="number">4.50 hrs</div>
            </div>
            <div class="card" style="background-color: #edf2f7;">
                <div><strong>Inversión Total</strong></div>
                <div class="number" style="color: #1a365d;">10.00 hrs</div>
            </div>
        </div>
        
        <h3>📅 Detalle de Ceremonias</h3>
        <table>
            <thead>
                <tr>
                    <th>Fecha</th>
                    <th>Día</th>
                    <th>Descripción</th>
                    <th>Horario</th>
                    <th>Duración (hrs)</th>
                </tr>
            </thead>
            <tbody>
                <tr><td>15/06/2026</td><td>Lunes</td><td><span class="badge-ceremonia">Ceremonia</span> [Equipo Tráfico] Daily</td><td>08:20 - 08:35</td><td><strong>0.25</strong></td></tr>
                <tr><td>16/06/2026</td><td>Martes</td><td><span class="badge-ceremonia">Ceremonia</span> [Equipo Tráfico] Daily</td><td>08:20 - 08:35</td><td><strong>0.25</strong></td></tr>
                <tr><td>16/06/2026</td><td>Martes</td><td><span class="badge-ceremonia">Ceremonia</span> [Equipo Tráfico] Refinamiento</td><td>10:00 - 11:30</td><td><strong>1.5</strong></td></tr>
                <tr><td>17/06/2026</td><td>Miércoles</td><td><span class="badge-ceremonia">Ceremonia</span> [Equipo Tráfico] Daily</td><td>08:20 - 08:35</td><td><strong>0.25</strong></td></tr>
                <tr><td>19/06/2026</td><td>Viernes</td><td><span class="badge-ceremonia">Ceremonia</span> [Equipo Tráfico] Daily</td><td>08:20 - 08:35</td><td><strong>0.25</strong></td></tr>
                <tr><td>19/06/2026</td><td>Viernes</td><td><span class="badge-ceremonia">Ceremonia</span> Retrospectiva e inicio de Sprint</td><td>10:00 - 12:00</td><td><strong>2.0</strong></td></tr>
            </tbody>
        </table>

        <h3>💬 Detalle de Reuniones</h3>
        <table>
            <thead>
                <tr>
                    <th>Fecha</th>
                    <th>Día</th>
                    <th>Descripción</th>
                    <th>Horario</th>
                    <th>Duración (hrs)</th>
                </tr>
            </thead>
            <tbody>
                <tr><td>16/06/2026</td><td>Martes</td><td><span class="badge-reunion">Reunión</span> Espacio para análisis del flujo de sensores de vehículos sin reporte</td><td>14:00 - 15:00</td><td><strong>1.0</strong></td></tr>
                <tr><td>17/06/2026</td><td>Miércoles</td><td><span class="badge-reunion">Reunión</span> Entrega de accesorios compatibles con la unidad GV58CG</td><td>14:00 - 15:00</td><td><strong>1.0</strong></td></tr>
                <tr><td>17/06/2026</td><td>Miércoles</td><td><span class="badge-reunion">Reunión</span> Revisemos: frecuencia de reporte de unidades</td><td>15:00 - 15:30</td><td><strong>0.5</strong></td></tr>
                <tr><td>17/06/2026</td><td>Miércoles</td><td><span class="badge-reunion">Reunión</span> Programación de despliegues APP</td><td>15:00 - 16:00</td><td><strong>1.0</strong></td></tr>
                <tr><td>18/06/2026</td><td>Jueves</td><td><span class="badge-reunion">Reunión</span> Sincronización técnica microservicios de mapas internos</td><td>09:00 - 11:00</td><td><strong>2.0</strong></td></tr>
            </tbody>
        </table>
    </div>

    <!-- Jhon Pelaez -->
    <div class="user-block">
        <h2>👤 Colaborador: Jhon_Pelaez@satrack.com</h2>
        <div class="summary-box">
            <div class="card">
                <div>Tiempo en Reuniones</div>
                <div class="number">28.00 hrs</div>
            </div>
            <div class="card">
                <div>Tiempo en Ceremonias</div>
                <div class="number">3.50 hrs</div>
            </div>
            <div class="card" style="background-color: #edf2f7;">
                <div><strong>Inversión Total</strong></div>
                <div class="number" style="color: #1a365d;">31.50 hrs</div>
            </div>
        </div>
        
        <h3>📅 Detalle de Ceremonias</h3>
        <table>
            <thead>
                <tr>
                    <th>Fecha</th>
                    <th>Día</th>
                    <th>Descripción</th>
                    <th>Horario</th>
                    <th>Duración (hrs)</th>
                </tr>
            </thead>
            <tbody>
                <tr><td>15/06/2026</td><td>Lunes</td><td><span class="badge-ceremonia">Ceremonia</span> [Equipo Tráfico] Daily</td><td>08:20 - 08:35</td><td><strong>0.25</strong></td></tr>
                <tr><td>16/06/2026</td><td>Martes</td><td><span class="badge-ceremonia">Ceremonia</span> [Equipo Tráfico] Daily</td><td>08:20 - 08:35</td><td><strong>0.25</strong></td></tr>
                <tr><td>16/06/2026</td><td>Martes</td><td><span class="badge-ceremonia">Ceremonia</span> [Equipo Tráfico] Refinamiento</td><td>10:00 - 11:30</td><td><strong>1.5</strong></td></tr>
                <tr><td>17/06/2026</td><td>Miércoles</td><td><span class="badge-ceremonia">Ceremonia</span> [Equipo Tráfico] Daily</td><td>08:20 - 08:35</td><td><strong>0.25</strong></td></tr>
                <tr><td>19/06/2026</td><td>Viernes</td><td><span class="badge-ceremonia">Ceremonia</span> [Equipo Tráfico] Daily</td><td>08:20 - 08:35</td><td><strong>0.25</strong></td></tr>
                <tr><td>19/06/2026</td><td>Viernes</td><td><span class="badge-ceremonia">Ceremonia</span> Retrospectiva e inicio de Sprint</td><td>10:00 - 12:00</td><td><strong>1.0</strong></td></tr>
            </tbody>
        </table>

        <h3>💬 Detalle de Reuniones</h3>
        <table>
            <thead>
                <tr>
                    <th>Fecha</th>
                    <th>Día</th>
                    <th>Descripción</th>
                    <th>Horario</th>
                    <th>Duración (hrs)</th>
                </tr>
            </thead>
            <tbody>
                <tr><td>15/06/2026</td><td>Lunes</td><td><span class="badge-reunion">Reunión</span> Definición Arquitectura de Datos / Analítica Avanzada</td><td>14:00 - 18:00</td><td><strong>4.0</strong></td></tr>
                <tr><td>16/06/2026</td><td>Martes</td><td><span class="badge-reunion">Reunión</span> Definición Arquitectura de Datos / Analítica Avanzada</td><td>14:00 - 18:00</td><td><strong>4.0</strong></td></tr>
                <tr><td>17/06/2026</td><td>Miércoles</td><td><span class="badge-reunion">Reunión</span> Definición Arquitectura de Datos / Analítica Avanzada</td><td>14:00 - 18:00</td><td><strong>4.0</strong></td></tr>
                <tr><td>18/06/2026</td><td>Jueves</td><td><span class="badge-reunion">Reunión</span> Definición Arquitectura de Datos / Analítica Avanzada</td><td>14:00 - 18:00</td><td><strong>4.0</strong></td></tr>
                <tr><td>19/06/2026</td><td>Viernes</td><td><span class="badge-reunion">Reunión</span> Definición Arquitectura de Datos / Analítica Avanzada</td><td>14:00 - 18:00</td><td><strong>4.0</strong></td></tr>
                <tr><td>15/06/2026</td><td>Lunes</td><td><span class="badge-reunion">Reunión</span> Alineación Técnica y Estratégica: Negocio Satrack 2026</td><td>09:00 - 12:00</td><td><strong>3.0</strong></td></tr>
                <tr><td>17/06/2026</td><td>Miércoles</td><td><span class="badge-reunion">Reunión</span> Sincronización de Líderes y Capítulos TI</td><td>09:00 - 11:00</td><td><strong>2.0</strong></td></tr>
                <tr><td>18/06/2026</td><td>Jueves</td><td><span class="badge-reunion">Reunión</span> Comités de Seguimiento y Revisión Trimestral</td><td>08:00 - 11:00</td><td><strong>3.0</strong></td></tr>
            </tbody>
        </table>
    </div>

    <!-- Leidy Ramirez -->
    <div class="user-block">
        <h2>👤 Colaborador: Leidy_Ramirez@satrack.com</h2>
        <div class="summary-box">
            <div class="card">
                <div>Tiempo en Reuniones</div>
                <div class="number">1.00 hrs</div>
            </div>
            <div class="card">
                <div>Tiempo en Ceremonias</div>
                <div class="number">3.50 hrs</div>
            </div>
            <div class="card" style="background-color: #edf2f7;">
                <div><strong>Inversión Total</strong></div>
                <div class="number" style="color: #1a365d;">4.50 hrs</div>
            </div>
        </div>
        
        <h3>📅 Detalle de Ceremonias</h3>
        <table>
            <thead>
                <tr>
                    <th>Fecha</th>
                    <th>Día</th>
                    <th>Descripción</th>
                    <th>Horario</th>
                    <th>Duración (hrs)</th>
                </tr>
            </thead>
            <tbody>
                <tr><td>15/06/2026</td><td>Lunes</td><td><span class="badge-ceremonia">Ceremonia</span> [Equipo Tráfico] Daily</td><td>08:20 - 08:35</td><td><strong>0.25</strong></td></tr>
                <tr><td>16/06/2026</td><td>Martes</td><td><span class="badge-ceremonia">Ceremonia</span> [Equipo Tráfico] Daily</td><td>08:20 - 08:35</td><td><strong>0.25</strong></td></tr>
                <tr><td>16/06/2026</td><td>Martes</td><td><span class="badge-ceremonia">Ceremonia</span> [Equipo Tráfico] Refinamiento</td><td>10:00 - 11:30</td><td><strong>1.5</strong></td></tr>
                <tr><td>17/06/2026</td><td>Miércoles</td><td><span class="badge-ceremonia">Ceremonia</span> [Equipo Tráfico] Daily</td><td>08:20 - 08:35</td><td><strong>0.25</strong></td></tr>
                <tr><td>19/06/2026</td><td>Viernes</td><td><span class="badge-ceremonia">Ceremonia</span> [Equipo Tráfico] Daily</td><td>08:20 - 08:35</td><td><strong>0.25</strong></td></tr>
                <tr><td>19/06/2026</td><td>Viernes</td><td><span class="badge-ceremonia">Ceremonia</span> Retrospectiva e inicio de Sprint</td><td>10:00 - 11:00</td><td><strong>1.0</strong></td></tr>
            </tbody>
        </table>

        <h3>💬 Detalle de Reuniones</h3>
        <table>
            <thead>
                <tr>
                    <th>Fecha</th>
                    <th>Día</th>
                    <th>Descripción</th>
                    <th>Horario</th>
                    <th>Duración (hrs)</th>
                </tr>
            </thead>
            <tbody>
                <tr><td>17/06/2026</td><td>Miércoles</td><td><span class="badge-reunion">Reunión</span> Entrega de accesorios compatibles con la unidad GV58CG</td><td>14:00 - 15:00</td><td><strong>1.0</strong></td></tr>
            </tbody>
        </table>
    </div>

    <!-- Percy Lucas -->
    <div class="user-block">
        <h2>👤 Colaborador: percy_lucas@satrack.com</h2>
        <div class="summary-box">
            <div class="card">
                <div>Tiempo en Reuniones</div>
                <div class="number">4.00 hrs</div>
            </div>
            <div class="card">
                <div>Tiempo en Ceremonias</div>
                <div class="number">3.50 hrs</div>
            </div>
            <div class="card" style="background-color: #edf2f7;">
                <div><strong>Inversión Total</strong></div>
                <div class="number" style="color: #1a365d;">7.50 hrs</div>
            </div>
        </div>
        
        <h3>📅 Detalle de Ceremonias</h3>
        <table>
            <thead>
                <tr>
                    <th>Fecha</th>
                    <th>Día</th>
                    <th>Descripción</th>
                    <th>Horario</th>
                    <th>Duración (hrs)</th>
                </tr>
            </thead>
            <tbody>
                <tr><td>15/06/2026</td><td>Lunes</td><td><span class="badge-ceremonia">Ceremonia</span> [Equipo Tráfico] Daily</td><td>08:20 - 08:35</td><td><strong>0.25</strong></td></tr>
                <tr><td>16/06/2026</td><td>Martes</td><td><span class="badge-ceremonia">Ceremonia</span> [Equipo Tráfico] Daily</td><td>08:20 - 08:35</td><td><strong>0.25</strong></td></tr>
                <tr><td>16/06/2026</td><td>Martes</td><td><span class="badge-ceremonia">Ceremonia</span> [Equipo Tráfico] Refinamiento</td><td>10:00 - 11:30</td><td><strong>1.5</strong></td></tr>
                <tr><td>17/06/2026</td><td>Miércoles</td><td><span class="badge-ceremonia">Ceremonia</span> [Equipo Tráfico] Daily</td><td>08:20 - 08:35</td><td><strong>0.25</strong></td></tr>
                <tr><td>19/06/2026</td><td>Viernes</td><td><span class="badge-ceremonia">Ceremonia</span> [Equipo Tráfico] Daily</td><td>08:20 - 08:35</td><td><strong>0.25</strong></td></tr>
                <tr><td>19/06/2026</td><td>Viernes</td><td><span class="badge-ceremonia">Ceremonia</span> Retrospectiva e inicio de Sprint</td><td>10:00 - 11:00</td><td><strong>1.0</strong></td></tr>
            </tbody>
        </table>

        <h3>💬 Detalle de Reuniones</h3>
        <table>
            <thead>
                <tr>
                    <th>Fecha</th>
                    <th>Día</th>
                    <th>Descripción</th>
                    <th>Horario</th>
                    <th>Duración (hrs)</th>
                </tr>
            </thead>
            <tbody>
                <tr><td>18/06/2026</td><td>Jueves</td><td><span class="badge-reunion">Reunión</span> Sincronización técnica microservicios de mapas internos</td><td>09:00 - 11:00</td><td><strong>2.0</strong></td></tr>
                <tr><td>17/06/2026</td><td>Miércoles</td><td><span class="badge-reunion">Reunión</span> Sincronización de Líderes y Capítulos TI</td><td>09:00 - 11:00</td><td><strong>2.0</strong></td></tr>
            </tbody>
        </table>
    </div>

</div>
</body>
</html>
