<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gerador de Romaneios</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
        }

        #print-area {
            display: none;
        }

        /* Estilos específicos para a Impressão */
        @media print {
            body * {
                visibility: hidden;
            }
            #print-area, #print-area * {
                visibility: visible;
            }
            #print-area {
                display: block;
                position: absolute;
                left: 0;
                top: 0;
                width: 100%;
            }
            .canhoto {
                page-break-inside: avoid;
                border: 1px solid #000 !important;
                padding: 0.3cm;
                margin-bottom: 0.6cm;
                box-sizing: border-box;
            }
            .canhoto-header h3 {
                font-size: 10pt;
                font-weight: bold;
                margin-bottom: 1px;
            }
            .canhoto-header p {
                font-size: 8pt;
                line-height: 1.1;
                margin: 0;
            }
            .canhoto-details .detail-row {
                font-size: 9pt;
                margin-bottom: 2px;
            }
            .canhoto-package {
                font-size: 10pt;
                font-weight: bold;
                margin-top: 4px;
                padding-top: 2px;
            }
            @page {
                size: A4;
                margin: 1.2cm;
            }
        }

        /* Estilos para a Visualização em Tela */
        .canhoto-preview {
            border: 1px dashed #9ca3af;
            background-color: #f9fafb;
            border-radius: 8px;
            padding: 16px;
            margin-bottom: 16px;
        }
        .canhoto-header {
            text-align: center;
            border-bottom: 1px solid #d1d5db;
            padding-bottom: 8px;
            margin-bottom: 12px;
        }
        .canhoto-header h3 {
            font-weight: 600;
            font-size: 1rem;
            margin: 0;
        }
        .canhoto-header p {
            margin: 2px 0;
            font-size: 0.8rem;
        }
        .canhoto-details .detail-row {
            display: flex;
            justify-content: space-between;
            margin-bottom: 8px;
            font-size: 0.9rem;
        }
        .canhoto-details .detail-row span {
            flex-basis: 48%;
        }
        .canhoto-package {
            text-align: center;
            font-weight: 700;
            font-size: 1.1rem;
            margin-top: 12px;
            padding-top: 8px;
            border-top: 1px solid #d1d5db;
        }
        .uppercase-input {
            text-transform: uppercase;
        }
    </style>
</head>
<body class="bg-gray-100 flex items-center justify-center min-h-screen py-10">
    <div class="container mx-auto p-4 max-w-4xl">
        <div class="bg-white rounded-lg shadow-lg p-8">
            <h1 class="text-2xl font-bold text-gray-800 mb-2">Gerador de Romaneios de Entrega</h1>
            <p class="text-gray-600 mb-6">Preencha os dados abaixo para gerar os canhotos de todos os pacotes.</p>

            <form id="romaneio-form" class="grid grid-cols-1 md:grid-cols-2 gap-x-8">
                <!-- Coluna da Esquerda -->
                <div>
                    <div class="mb-4">
                        <label for="cliente" class="block text-sm font-medium text-gray-700">Cliente</label>
                        <input type="text" id="cliente" name="cliente" required class="uppercase-input mt-1 block w-full px-3 py-2 bg-white border border-gray-300 rounded-md shadow-sm focus:outline-none focus:ring-indigo-500 focus:border-indigo-500">
                    </div>
                    <div class="mb-4">
                        <label for="vendedor" class="block text-sm font-medium text-gray-700">Vendedor</label>
                        <input type="text" id="vendedor" name="vendedor" required class="uppercase-input mt-1 block w-full px-3 py-2 bg-white border border-gray-300 rounded-md shadow-sm focus:outline-none focus:ring-indigo-500 focus:border-indigo-500">
                    </div>
                </div>

                <!-- Coluna da Direita -->
                <div>
                    <div class="mb-4">
                        <label for="pv_number" class="block text-sm font-medium text-gray-700">PV</label>
                        <div class="flex items-center space-x-2">
                            <span class="text-gray-500 pt-1">PV-</span>
                            <input type="text" id="pv_number" name="pv_number" placeholder="000000000" maxlength="9" oninput="this.value = this.value.replace(/\D/g,'')" class="mt-1 block w-full px-3 py-2 bg-white border border-gray-300 rounded-md shadow-sm focus:outline-none focus:ring-indigo-500 focus:border-indigo-500">
                            <span class="text-gray-500 pt-1">/</span>
                            <select id="pv_year" name="pv_year" class="mt-1 block w-auto px-3 py-2 bg-white border border-gray-300 rounded-md shadow-sm focus:outline-none focus:ring-indigo-500 focus:border-indigo-500">
                                <!-- Anos populados via JS -->
                            </select>
                        </div>
                    </div>
                     <div class="mb-4">
                        <label for="codigo" class="block text-sm font-medium text-gray-700">Código</label>
                        <input type="text" id="codigo" name="codigo" class="uppercase-input mt-1 block w-full px-3 py-2 bg-white border border-gray-300 rounded-md shadow-sm focus:outline-none focus:ring-indigo-500 focus:border-indigo-500">
                    </div>
                    <div class="grid grid-cols-2 gap-4">
                         <div>
                            <label for="data" class="block text-sm font-medium text-gray-700">Data</label>
                            <input type="date" id="data" name="data" required class="mt-1 block w-full px-3 py-2 bg-white border border-gray-300 rounded-md shadow-sm focus:outline-none focus:ring-indigo-500 focus:border-indigo-500">
                        </div>
                        <div>
                            <label for="pacotes" class="block text-sm font-medium text-gray-700">Nº de Pacotes</label>
                            <input type="number" id="pacotes" name="pacotes" required min="1" value="1" class="mt-1 block w-full px-3 py-2 bg-white border border-gray-300 rounded-md shadow-sm focus:outline-none focus:ring-indigo-500 focus:border-indigo-500">
                        </div>
                    </div>
                </div>

                <div class="md:col-span-2 flex items-center justify-end space-x-4 mt-4">
                     <button type="button" id="clear-btn" class="px-6 py-2 border border-gray-300 rounded-md shadow-sm text-sm font-medium text-gray-700 bg-white hover:bg-gray-50 focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-indigo-500">Limpar</button>
                    <button type="submit" class="px-6 py-2 border border-transparent rounded-md shadow-sm text-sm font-medium text-white bg-indigo-600 hover:bg-indigo-700 focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-indigo-500">Gerar Romaneios</button>
                </div>
            </form>

            <div id="actions-bar" class="hidden mt-6 text-right">
                <button id="print-btn" class="px-6 py-2 border border-transparent rounded-md shadow-sm text-sm font-medium text-white bg-green-600 hover:bg-green-700 focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-green-500">
                    Imprimir
                </button>
            </div>
             <div id="preview-area" class="mt-8 hidden">
                <h2 class="text-xl font-semibold text-gray-700 mb-4">Pré-visualização para Impressão</h2>
                <div id="preview-content" class="max-h-96 overflow-y-auto p-4 bg-gray-50 rounded-lg border">
                </div>
            </div>
        </div>
    </div>

    <div id="print-area"></div>

    <script>
        document.addEventListener('DOMContentLoaded', () => {
            const form = document.getElementById('romaneio-form');
            const printArea = document.getElementById('print-area');
            const previewContent = document.getElementById('preview-content');
            const actionsBar = document.getElementById('actions-bar');
            const printBtn = document.getElementById('print-btn');
            const clearBtn = document.getElementById('clear-btn');
            const previewArea = document.getElementById('preview-area');
            const dataField = document.getElementById('data');

            // --- NOVAS FUNÇÕES ---
            function setupUppercaseInputs() {
                const fields = document.querySelectorAll('.uppercase-input');
                fields.forEach(field => {
                    field.addEventListener('input', (e) => {
                        e.target.value = e.target.value.toUpperCase();
                    });
                });
            }

            function populateYearSelect() {
                const yearSelect = document.getElementById('pv_year');
                const currentYear = new Date().getFullYear();
                const startYear = currentYear;
                const endYear = startYear - 10;

                for (let year = startYear; year >= endYear; year--) {
                    const option = document.createElement('option');
                    option.value = String(year).slice(-2);
                    option.textContent = year;
                    yearSelect.appendChild(option);
                }
            }

            // --- INICIALIZAÇÃO ---
            dataField.value = new Date().toISOString().split('T')[0];
            setupUppercaseInputs();
            populateYearSelect();

            form.addEventListener('submit', (e) => {
                e.preventDefault();

                const formData = new FormData(form);
                const data = Object.fromEntries(formData.entries());
                const totalPacotes = parseInt(data.pacotes, 10);
                
                printArea.innerHTML = '';
                previewContent.innerHTML = '';

                // Formata o PV
                const pvNumber = data.pv_number || '';
                const pvYear = data.pv_year || '';
                const formattedPV = pvNumber ? `PV-${pvNumber.padStart(9, '0')}/${pvYear}` : '';

                for (let i = 1; i <= totalPacotes; i++) {
                    const canhotoContent = `
                        <div class="canhoto-header">
                            <h3>J ALVES E OLIVEIRA LTDA</h3>
                            <p>RUA CEL. ERNESTO DEOCLECIANO, 510 CENTRO - SOBRAL-CE</p>
                            <p><strong>SOBRAL IV - LOJA 63 (LOJA/MOSTRUÁRIO)</strong></p>
                        </div>
                        <div class="canhoto-details">
                            <div class="detail-row">
                                <span><strong>CLIENTE:</strong> ${data.cliente || ''}</span>
                                <span><strong>VENDEDOR:</strong> ${data.vendedor || ''}</span>
                            </div>
                            <div class="detail-row">
                                <span><strong>PV:</strong> ${formattedPV}</span>
                                <span><strong>CÓDIGO:</strong> ${data.codigo || ''}</span>
                            </div>
                            <div class="detail-row">
                                <span><strong>DATA:</strong> ${new Date(data.data).toLocaleDateString('pt-BR', {timeZone: 'UTC'})}</span>
                                <span></span>
                            </div>
                        </div>
                        <div class="canhoto-package">
                            PACOTE: ${i} de ${totalPacotes}
                        </div>
                    `;
                    
                    const printCanhoto = `<div class="canhoto">${canhotoContent}</div>`;
                    const previewCanhoto = `<div class="canhoto-preview">${canhotoContent}</div>`;

                    if (i > 1 && (i - 1) % 4 === 0) {
                       printArea.innerHTML += `<div style="page-break-after: always;"></div>`;
                    }
                    printArea.innerHTML += printCanhoto;
                    previewContent.innerHTML += previewCanhoto;
                }

                actionsBar.classList.remove('hidden');
                previewArea.classList.remove('hidden');
            });

            printBtn.addEventListener('click', () => {
                window.print();
            });

            clearBtn.addEventListener('click', () => {
                form.reset();
                dataField.value = new Date().toISOString().split('T')[0];
                document.getElementById('pv_year').value = String(new Date().getFullYear()).slice(-2);
                actionsBar.classList.add('hidden');
                previewArea.classList.add('hidden');
                printArea.innerHTML = '';
                previewContent.innerHTML = '';
            });
        });
    </script>
</body>
</html>


