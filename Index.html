<!DOCTYPE html>
<html lang="th">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ระบบรายงานอ้อยเข้าหีบ ปี 68/69</title>
    <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Sarabun:wght@300;400;500;600&display=swap">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Sarabun', sans-serif;
        }

        :root {
            --primary: #2E7D32;
            --primary-light: #4CAF50;
            --secondary: #FF9800;
            --danger: #F44336;
            --warning: #FFC107;
            --light: #f8f9fa;
            --dark: #343a40;
            --gray: #6c757d;
            --border: #dee2e6;
        }

        body {
            background-color: #f5f5f5;
            color: var(--dark);
            line-height: 1.6;
        }

        .container {
            max-width: 1400px;
            margin: 0 auto;
            padding: 0 15px;
        }

        /* Header */
        header {
            background-color: white;
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
            position: sticky;
            top: 0;
            z-index: 100;
        }

        .header-content {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 15px 0;
        }

        .logo {
            display: flex;
            align-items: center;
            gap: 15px;
        }

        .logo i {
            font-size: 2rem;
            color: var(--primary);
        }

        .logo h1 {
            font-size: 1.5rem;
            font-weight: 600;
            color: var(--primary);
        }

        /* Navigation */
        nav {
            background-color: var(--primary);
        }

        .nav-menu {
            display: flex;
            list-style: none;
        }

        .nav-menu li {
            position: relative;
        }

        .nav-menu a {
            display: block;
            padding: 15px 20px;
            color: white;
            text-decoration: none;
            font-weight: 500;
            transition: background-color 0.3s;
        }

        .nav-menu a:hover {
            background-color: rgba(255, 255, 255, 0.1);
        }

        .nav-menu a.active {
            background-color: rgba(255, 255, 255, 0.2);
        }

        .nav-menu a i {
            margin-right: 8px;
        }

        /* Main Content */
        main {
            padding: 30px 0;
            min-height: calc(100vh - 140px);
        }

        .page-title {
            margin-bottom: 30px;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        .page-title h2 {
            font-size: 1.8rem;
            color: var(--primary);
            font-weight: 600;
        }

        /* Summary Cards */
        .summary-cards {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            margin-bottom: 30px;
        }

        .card {
            background-color: white;
            border-radius: 10px;
            padding: 20px;
            box-shadow: 0 4px 6px rgba(0,0,0,0.05);
            transition: transform 0.3s, box-shadow 0.3s;
        }

        .card:hover {
            transform: translateY(-5px);
            box-shadow: 0 8px 15px rgba(0,0,0,0.1);
        }

        .card-header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin-bottom: 15px;
        }

        .card-icon {
            width: 50px;
            height: 50px;
            border-radius: 10px;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 1.5rem;
        }

        .card-icon.file {
            background-color: #E3F2FD;
            color: #1976D2;
        }

        .card-icon.data {
            background-color: #F3E5F5;
            color: #7B1FA2;
        }

        .card-icon.weight {
            background-color: #E8F5E9;
            color: var(--primary);
        }

        .card-icon.quota {
            background-color: #FFF3E0;
            color: #EF6C00;
        }

        .card-value {
            font-size: 2rem;
            font-weight: 600;
            margin-bottom: 5px;
        }

        .card-label {
            color: var(--gray);
            font-size: 0.9rem;
        }

        /* Upload Section */
        .upload-section {
            background-color: white;
            border-radius: 10px;
            padding: 25px;
            box-shadow: 0 4px 6px rgba(0,0,0,0.05);
            margin-bottom: 30px;
        }

        .section-title {
            font-size: 1.4rem;
            color: var(--primary);
            margin-bottom: 20px;
            padding-bottom: 10px;
            border-bottom: 1px solid var(--border);
        }

        .section-title i {
            margin-right: 10px;
        }

        .upload-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
        }

        .upload-area {
            border: 2px dashed var(--border);
            border-radius: 10px;
            padding: 25px;
            text-align: center;
            cursor: pointer;
            transition: all 0.3s;
            background-color: #fafafa;
            position: relative;
            overflow: hidden;
        }

        .upload-area:hover {
            border-color: var(--primary-light);
            background-color: #f0fff0;
        }

        .upload-area.active {
            border-color: var(--primary);
            background-color: #E8F5E9;
        }

        .upload-area.error {
            border-color: var(--danger);
            background-color: #FFEBEE;
        }

        .upload-icon {
            font-size: 3rem;
            color: var(--gray);
            margin-bottom: 15px;
        }

        .upload-area:hover .upload-icon {
            color: var(--primary);
        }

        .upload-title {
            font-size: 1.2rem;
            font-weight: 500;
            margin-bottom: 10px;
            color: var(--dark);
        }

        .upload-info {
            color: var(--gray);
            font-size: 0.9rem;
            margin-bottom: 15px;
        }

        .upload-btn {
            background-color: var(--primary-light);
            color: white;
            border: none;
            padding: 8px 20px;
            border-radius: 5px;
            cursor: pointer;
            font-weight: 500;
            transition: background-color 0.3s;
        }

        .upload-btn:hover {
            background-color: var(--primary);
        }

        .file-input {
            position: absolute;
            width: 100%;
            height: 100%;
            top: 0;
            left: 0;
            opacity: 0;
            cursor: pointer;
        }

        .file-status {
            margin-top: 15px;
            padding: 10px;
            border-radius: 5px;
            background-color: #f8f9fa;
            font-size: 0.9rem;
        }

        .file-name {
            font-weight: 500;
            color: var(--dark);
            word-break: break-all;
        }

        .file-size {
            color: var(--gray);
            font-size: 0.85rem;
        }

        .progress-bar {
            height: 6px;
            background-color: var(--border);
            border-radius: 3px;
            margin-top: 8px;
            overflow: hidden;
        }

        .progress-fill {
            height: 100%;
            background-color: var(--primary);
            width: 0%;
            transition: width 0.5s;
        }

        .status-text {
            display: inline-block;
            padding: 3px 10px;
            border-radius: 20px;
            font-size: 0.8rem;
            font-weight: 500;
        }

        .status-text.pending {
            background-color: #FFF3CD;
            color: #856404;
        }

        .status-text.success {
            background-color: #D4EDDA;
            color: #155724;
        }

        .status-text.error {
            background-color: #F8D7DA;
            color: #721C24;
        }

        /* Sample Data Section */
        .sample-section {
            background-color: white;
            border-radius: 10px;
            padding: 25px;
            box-shadow: 0 4px 6px rgba(0,0,0,0.05);
            margin-bottom: 30px;
        }

        .table-container {
            overflow-x: auto;
            margin-top: 20px;
        }

        table {
            width: 100%;
            border-collapse: collapse;
            min-width: 600px;
        }

        thead {
            background-color: #f8f9fa;
        }

        th {
            padding: 12px 15px;
            text-align: left;
            font-weight: 600;
            color: var(--dark);
            border-bottom: 2px solid var(--border);
            white-space: nowrap;
        }

        td {
            padding: 12px 15px;
            border-bottom: 1px solid var(--border);
            white-space: nowrap;
        }

        tbody tr:hover {
            background-color: #f8f9fa;
        }

        .no-data {
            text-align: center;
            padding: 30px;
            color: var(--gray);
            font-style: italic;
        }

        /* Status Panel */
        .status-panel {
            background-color: white;
            border-radius: 10px;
            padding: 25px;
            box-shadow: 0 4px 6px rgba(0,0,0,0.05);
            margin-bottom: 30px;
        }

        .status-list {
            margin-bottom: 20px;
        }

        .status-item {
            display: flex;
            align-items: center;
            padding: 12px 15px;
            margin-bottom: 10px;
            border-radius: 8px;
            background-color: #f8f9fa;
        }

        .status-icon {
            font-size: 1.2rem;
            margin-right: 15px;
            width: 30px;
            text-align: center;
        }

        .status-icon.pending {
            color: var(--warning);
        }

        .status-icon.success {
            color: var(--primary);
        }

        .status-icon.error {
            color: var(--danger);
        }

        .status-content {
            flex-grow: 1;
        }

        .status-title {
            font-weight: 500;
            margin-bottom: 3px;
        }

        .status-desc {
            font-size: 0.9rem;
            color: var(--gray);
        }

        .validation-summary {
            border-top: 1px solid var(--border);
            padding-top: 20px;
        }

        .validation-title {
            font-size: 1.2rem;
            margin-bottom: 15px;
            color: var(--dark);
        }

        .validation-list {
            list-style: none;
        }

        .validation-list li {
            padding: 8px 0;
            display: flex;
            align-items: flex-start;
        }

        .validation-list i {
            margin-right: 10px;
            margin-top: 3px;
        }

        .validation-list .success {
            color: var(--primary);
        }

        .validation-list .error {
            color: var(--danger);
        }

        .validation-list .warning {
            color: var(--warning);
        }

        /* Action Buttons */
        .action-buttons {
            display: flex;
            gap: 15px;
            justify-content: center;
            margin-top: 30px;
        }

        .btn {
            padding: 12px 30px;
            border: none;
            border-radius: 8px;
            font-weight: 500;
            cursor: pointer;
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 10px;
            transition: all 0.3s;
            font-size: 1rem;
        }

        .btn i {
            font-size: 1.1rem;
        }

        .btn-primary {
            background-color: var(--primary);
            color: white;
        }

        .btn-primary:hover {
            background-color: #1B5E20;
            transform: translateY(-2px);
            box-shadow: 0 5px 10px rgba(46, 125, 50, 0.2);
        }

        .btn-secondary {
            background-color: #6c757d;
            color: white;
        }

        .btn-secondary:hover {
            background-color: #545b62;
            transform: translateY(-2px);
        }

        .btn-success {
            background-color: #28a745;
            color: white;
        }

        .btn-success:hover {
            background-color: #218838;
            transform: translateY(-2px);
        }

        .btn:disabled {
            background-color: #cccccc;
            cursor: not-allowed;
            transform: none;
            box-shadow: none;
        }

        /* Dashboard Section */
        .dashboard-section {
            background-color: white;
            border-radius: 10px;
            padding: 25px;
            box-shadow: 0 4px 6px rgba(0,0,0,0.05);
            margin-bottom: 30px;
            display: none;
        }

        .mode-selector {
            display: flex;
            gap: 15px;
            margin-bottom: 25px;
        }

        .mode-btn {
            padding: 10px 25px;
            border: 2px solid var(--border);
            border-radius: 8px;
            background: white;
            cursor: pointer;
            font-weight: 500;
            transition: all 0.3s;
        }

        .mode-btn.active {
            background-color: var(--primary);
            color: white;
            border-color: var(--primary);
        }

        .mode-btn:hover:not(.active) {
            background-color: #f8f9fa;
        }

        .view-selector {
            display: flex;
            gap: 15px;
            margin-bottom: 20px;
            align-items: center;
            flex-wrap: wrap;
        }

        .view-btn {
            padding: 8px 20px;
            border: 1px solid var(--border);
            border-radius: 5px;
            background: white;
            cursor: pointer;
            transition: all 0.3s;
        }

        .view-btn.active {
            background-color: var(--primary-light);
            color: white;
            border-color: var(--primary-light);
        }

        .chart-container {
            position: relative;
            height: 500px;
            margin: 20px 0;
            border: 1px solid var(--border);
            border-radius: 8px;
            padding: 15px;
            background-color: white;
        }

        .chart-title {
            text-align: center;
            font-size: 24px;
            font-weight: bold;
            margin-bottom: 20px;
            color: var(--primary);
        }

        .chart-subtitle {
            text-align: center;
            font-size: 18px;
            margin-bottom: 10px;
            color: var(--dark);
        }

        .chart-date {
            text-align: center;
            font-size: 16px;
            margin-bottom: 20px;
            color: var(--gray);
        }

        .chart-controls {
            display: flex;
            justify-content: center;
            gap: 10px;
            margin-bottom: 20px;
            flex-wrap: wrap;
        }

        .chart-summary {
            display: grid;
            grid-template-columns: 1fr;
            gap: 15px;
            margin-top: 25px;
        }

        .summary-item {
            background-color: #f8f9fa;
            padding: 15px;
            border-radius: 8px;
            text-align: center;
        }

        .summary-value {
            font-size: 1.8rem;
            font-weight: 600;
            color: var(--primary);
            margin-bottom: 5px;
        }

        .summary-label {
            color: var(--gray);
            font-size: 0.9rem;
        }

        .zone-legend {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
            margin-top: 15px;
            justify-content: center;
        }

        .legend-item {
            display: flex;
            align-items: center;
            gap: 5px;
            font-size: 0.9rem;
        }

        .legend-color {
            width: 15px;
            height: 15px;
            border-radius: 3px;
        }

        /* Responsive */
        @media (max-width: 768px) {
            .header-content {
                flex-direction: column;
                gap: 15px;
                text-align: center;
            }
            
            .nav-menu {
                flex-wrap: wrap;
                justify-content: center;
            }
            
            .nav-menu a {
                padding: 10px 15px;
                font-size: 0.9rem;
            }
            
            .summary-cards {
                grid-template-columns: 1fr;
            }
            
            .upload-grid {
                grid-template-columns: 1fr;
            }
            
            .action-buttons {
                flex-direction: column;
            }
            
            .btn {
                width: 100%;
            }
            
            .mode-selector, .view-selector {
                flex-direction: column;
            }
            
            .mode-btn, .view-btn {
                width: 100%;
            }
            
            .chart-controls {
                flex-direction: column;
            }
        }

        /* Loading */
        .loading {
            display: inline-block;
            width: 20px;
            height: 20px;
            border: 3px solid rgba(255,255,255,.3);
            border-radius: 50%;
            border-top-color: white;
            animation: spin 1s ease-in-out infinite;
        }

        @keyframes spin {
            to { transform: rotate(360deg); }
        }
    </style>
</head>
<body>
    <!-- Header -->
    <header>
        <div class="container">
            <div class="header-content">
                <div class="logo">
                    <i class="fas fa-tractor"></i>
                    <h1>ระบบรายงานอ้อยเข้าหีบ ปี 68/69</h1>
                </div>
            </div>
        </div>
    </header>

    <!-- Navigation -->
    <nav>
        <div class="container">
            <ul class="nav-menu">
                <li><a href="#" class="active"><i class="fas fa-home"></i> หน้าหลัก</a></li>
                <li><a href="#"><i class="fas fa-upload"></i> อัพโหลดไฟล์</a></li>
                <li><a href="#" onclick="showReportPage()"><i class="fas fa-chart-bar"></i> รายงาน</a></li>
                <li><a href="#"><i class="fas fa-cog"></i> ตั้งค่า</a></li>
                <li><a href="#"><i class="fas fa-question-circle"></i> ช่วยเหลือ</a></li>
            </ul>
        </div>
    </nav>

    <!-- Main Content -->
    <main class="container" id="mainContent">
        <!-- Page Title -->
        <div class="page-title">
            <h2><i class="fas fa-upload"></i> อัพโหลดไฟล์ข้อมูลอ้อยเข้าหีบ</h2>
            <div class="current-date">วันที่ 1 มกราคม 2569</div>
        </div>

        <!-- Summary Cards -->
        <div class="summary-cards">
            <div class="card">
                <div class="card-header">
                    <div>
                        <div class="card-value" id="fileCount">0/3</div>
                        <div class="card-label">ไฟล์ที่อัพโหลดแล้ว</div>
                    </div>
                    <div class="card-icon file">
                        <i class="fas fa-file-csv"></i>
                    </div>
                </div>
            </div>
            <div class="card">
                <div class="card-header">
                    <div>
                        <div class="card-value" id="totalRows">0</div>
                        <div class="card-label">แถวข้อมูลทั้งหมด</div>
                    </div>
                    <div class="card-icon data">
                        <i class="fas fa-database"></i>
                    </div>
                </div>
            </div>
            <div class="card">
                <div class="card-header">
                    <div>
                        <div class="card-value" id="totalWeight">0</div>
                        <div class="card-label">น้ำหนักอ้อยสุทธิ (ตัน)</div>
                    </div>
                    <div class="card-icon weight">
                        <i class="fas fa-weight-hanging"></i>
                    </div>
                </div>
            </div>
            <div class="card">
                <div class="card-header">
                    <div>
                        <div class="card-value" id="percentageTarget">0%</div>
                        <div class="card-label">ตันเข้าหีบ เทียบเป้าหมาย 2,400,000 ตัน</div>
                    </div>
                    <div class="card-icon quota">
                        <i class="fas fa-percentage"></i>
                    </div>
                </div>
            </div>
        </div>

        <!-- Upload Section -->
        <section class="upload-section">
            <h3 class="section-title"><i class="fas fa-cloud-upload-alt"></i> อัพโหลดไฟล์ข้อมูล</h3>
            <p style="color: var(--gray); margin-bottom: 15px;">กรุณาอัพโหลดไฟล์ข้อมูลทั้ง 3 ไฟล์ก่อนดำเนินการต่อ (ไฟล์ CSV ไม่เกิน 100MB)</p>
            
            <div class="upload-grid">
                <!-- File 1 -->
                <div class="upload-area" id="uploadArea1" onclick="document.getElementById('file1').click()">
                    <input type="file" id="file1" class="file-input" accept=".csv" onchange="handleFileUpload(this, 'kranburi')">
                    <div class="upload-icon">
                        <i class="fas fa-file-import"></i>
                    </div>
                    <div class="upload-title">ไฟล์อ้อยเข้าหีบ ครบุรี</div>
                    <div class="upload-info">ไฟล์ CSV | ขนาดไม่เกิน 100MB</div>
                    <button class="upload-btn">เลือกไฟล์</button>
                    
                    <div class="file-status" id="fileStatus1" style="display: none;">
                        <div class="file-name" id="fileName1"></div>
                        <div class="file-size" id="fileSize1"></div>
                        <div class="progress-bar">
                            <div class="progress-fill" id="progress1"></div>
                        </div>
                        <div class="status-text pending" id="statusText1">รออัพโหลด</div>
                    </div>
                </div>

                <!-- File 2 -->
                <div class="upload-area" id="uploadArea2" onclick="document.getElementById('file2').click()">
                    <input type="file" id="file2" class="file-input" accept=".csv" onchange="handleFileUpload(this, 'sikhio')">
                    <div class="upload-icon">
                        <i class="fas fa-file-import"></i>
                    </div>
                    <div class="upload-title">ไฟล์อ้อยเข้าหีบ สีคิ้ว</div>
                    <div class="upload-info">ไฟล์ CSV | ขนาดไม่เกิน 100MB</div>
                    <button class="upload-btn">เลือกไฟล์</button>
                    
                    <div class="file-status" id="fileStatus2" style="display: none;">
                        <div class="file-name" id="fileName2"></div>
                        <div class="file-size" id="fileSize2"></div>
                        <div class="progress-bar">
                            <div class="progress-fill" id="progress2"></div>
                        </div>
                        <div class="status-text pending" id="statusText2">รออัพโหลด</div>
                    </div>
                </div>

                <!-- File 3 -->
                <div class="upload-area" id="uploadArea3" onclick="document.getElementById('file3').click()">
                    <input type="file" id="file3" class="file-input" accept=".csv" onchange="handleFileUpload(this, 'farmers')">
                    <div class="upload-icon">
                        <i class="fas fa-file-import"></i>
                    </div>
                    <div class="upload-title">ฐานข้อมูลชาวไร่</div>
                    <div class="upload-info">ไฟล์ CSV | ขนาดไม่เกิน 100MB</div>
                    <button class="upload-btn">เลือกไฟล์</button>
                    
                    <div class="file-status" id="fileStatus3" style="display: none;">
                        <div class="file-name" id="fileName3"></div>
                        <div class="file-size" id="fileSize3"></div>
                        <div class="progress-bar">
                            <div class="progress-fill" id="progress3"></div>
                        </div>
                        <div class="status-text pending" id="statusText3">รออัพโหลด</div>
                    </div>
                </div>
            </div>
        </section>

        <!-- Sample Data Section -->
        <section class="sample-section">
            <h3 class="section-title"><i class="fas fa-table"></i> ตัวอย่างข้อมูล</h3>
            <p style="color: var(--gray); margin-bottom: 15px;">แสดงข้อมูลตัวอย่าง 5 แถวแรกของไฟล์ที่อัพโหลดล่าสุด (แสดงคอลัมน์ทั้งหมด)</p>
            
            <div class="table-container">
                <table id="sampleTable">
                    <thead>
                        <tr id="tableHeader">
                            <th>ไฟล์</th>
                            <th>ตัวอย่างข้อมูล (5 แถวแรก)</th>
                        </tr>
                    </thead>
                    <tbody id="tableBody">
                        <tr>
                            <td colspan="2" class="no-data">ยังไม่มีข้อมูล กรุณาอัพโหลดไฟล์</td>
                        </tr>
                    </tbody>
                </table>
            </div>
        </section>

        <!-- Status Panel -->
        <section class="status-panel">
            <h3 class="section-title"><i class="fas fa-clipboard-check"></i> สถานะการตรวจสอบ</h3>
            
            <div class="status-list">
                <div class="status-item">
                    <div class="status-icon pending" id="statusIcon1">
                        <i class="fas fa-clock"></i>
                    </div>
                    <div class="status-content">
                        <div class="status-title">ไฟล์อ้อยเข้าหีบ ครบุรี</div>
                        <div class="status-desc" id="statusDesc1">รออัพโหลดไฟล์</div>
                    </div>
                </div>
                
                <div class="status-item">
                    <div class="status-icon pending" id="statusIcon2">
                        <i class="fas fa-clock"></i>
                    </div>
                    <div class="status-content">
                        <div class="status-title">ไฟล์อ้อยเข้าหีบ สีคิ้ว</div>
                        <div class="status-desc" id="statusDesc2">รออัพโหลดไฟล์</div>
                    </div>
                </div>
                
                <div class="status-item">
                    <div class="status-icon pending" id="statusIcon3">
                        <i class="fas fa-clock"></i>
                    </div>
                    <div class="status-content">
                        <div class="status-title">ฐานข้อมูลชาวไร่</div>
                        <div class="status-desc" id="statusDesc3">รออัพโหลดไฟล์</div>
                    </div>
                </div>
            </div>
            
            <div class="validation-summary" id="validationSummary" style="display: none;">
                <h4 class="validation-title">สรุปผลการตรวจสอบ</h4>
                <ul class="validation-list" id="validationResults">
                    <!-- Validation results will be inserted here -->
                </ul>
            </div>
        </section>

        <!-- Action Buttons -->
        <div class="action-buttons">
            <button class="btn btn-primary" id="validateBtn" onclick="validateAllFiles()" disabled>
                <i class="fas fa-search"></i> ตรวจสอบข้อมูล
            </button>
            <button class="btn btn-success" id="generateReportBtn" onclick="generateReport()" disabled>
                <i class="fas fa-chart-bar"></i> แสดงรายงาน
            </button>
            <button class="btn btn-secondary" id="downloadBtn" onclick="downloadReport()" disabled>
                <i class="fas fa-download"></i> ดาวน์โหลดรายงาน
            </button>
            <button class="btn" onclick="resetAll()">
                <i class="fas fa-redo"></i> ล้างข้อมูล
            </button>
        </div>
    </main>

    <!-- Report Page (Hidden initially) -->
    <main class="container" id="reportContent" style="display: none;">
        <!-- Page Title -->
        <div class="page-title">
            <h2><i class="fas fa-chart-bar"></i> Dashboard รายงานอ้อยเข้าหีบ</h2>
            <div class="current-date">วันที่ 1 มกราคม 2569</div>
        </div>

        <!-- Dashboard Section -->
        <section class="dashboard-section" id="dashboardSection">
            <!-- Chart Title Area -->
            <div id="chartTitleArea" style="text-align: center; margin-bottom: 20px; display: none;">
                <h2 class="chart-title">รายงานอ้อยเข้าหีบ ปี 68/69</h2>
                <h3 class="chart-subtitle" id="chartSubtitle">โรงงานครบุรี</h3>
                <p class="chart-date" id="chartDate">วันที่ 7/12/68 - 31/01/69</p>
            </div>
            
            <div class="view-selector">
                <span>มุมมอง:</span>
                <button class="view-btn active" onclick="selectView('all')">สะสมทั้งหมด</button>
                <button class="view-btn" onclick="selectView('byZone')">รายเขต</button>
                <button class="btn btn-success" onclick="saveChartAsImage()" style="margin-left: auto;">
                    <i class="fas fa-save"></i> บันทึกรายงาน
                </button>
            </div>
            
            <div class="chart-controls" id="allViewControls" style="display: flex;">
                <span>พื้นที่:</span>
                <button class="mode-btn active" onclick="selectMode('kranburi')">ครบุรี</button>
                <button class="mode-btn" onclick="selectMode('sikhio')">สีคิ้ว</button>
            </div>
            
            <div class="chart-controls" id="zoneViewControls" style="display: none; flex-wrap: wrap;">
                <span>พื้นที่:</span>
                <button class="mode-btn active" onclick="selectZoneMode('kranburi')">ครบุรี</button>
                <button class="mode-btn" onclick="selectZoneMode('sikhio')">สีคิ้ว</button>
                
                <div style="width: 100%; margin-top: 10px;">
                    <span>เลือกเขต:</span>
                    <div class="zone-buttons" id="zoneButtons" style="display: inline-flex; flex-wrap: wrap; gap: 5px; margin-left: 10px;"></div>
                </div>
            </div>
            
            <div class="chart-container">
                <canvas id="sugarChart"></canvas>
            </div>
            
            <div class="zone-legend" id="zoneLegend"></div>
            
            <div class="chart-summary">
                <div class="summary-item">
                    <div class="summary-value" id="totalWeightDashboard">0</div>
                    <div class="summary-label">น้ำหนักอ้อยสุทธิรวม (ตัน)</div>
                </div>
            </div>
        </section>
        
        <!-- Action Buttons for Report Page -->
        <div class="action-buttons">
            <button class="btn btn-primary" onclick="showMainPage()">
                <i class="fas fa-arrow-left"></i> กลับหน้าหลัก
            </button>
            <button class="btn btn-success" onclick="saveChartAsImage()">
                <i class="fas fa-save"></i> บันทึกรายงาน
            </button>
            <button class="btn btn-secondary" onclick="downloadReport()">
                <i class="fas fa-download"></i> ดาวน์โหลดรายงาน
            </button>
        </div>
    </main>

    <script>
        // เก็บข้อมูลใน memory
        const uploadedFiles = {
            kranburi: null,
            sikhio: null,
            farmers: null
        };

        // ข้อมูลเขตการทำงาน
        const zones = {
            kranburi: ["1", "2", "3", "4", "5", "6", "7", "8", "10", "11", "12", "21"],
            sikhio: ["C1", "C2", "C3", "C4"]
        };

        // เป้าหมายแต่ละเขต (ตัน/วัน) และการตั้งค่าแกน Y
        const zoneConfigs = {
            // ครบุรี
            "1": { target: 2000, stepSize: 200, max: 3000, minorStep: 100 },
            "2": { target: 2200, stepSize: 200, max: 3000, minorStep: 100 },
            "3": { target: 1500, stepSize: 200, max: 2000, minorStep: 100 },
            "4": { target: 1700, stepSize: 200, max: 2000, minorStep: 100 },
            "5": { target: 2800, stepSize: 200, max: 3000, minorStep: 100 },
            "6": { target: 2600, stepSize: 200, max: 3000, minorStep: 100 },
            "7": { target: 2200, stepSize: 200, max: 3000, minorStep: 100 },
            "8": { target: 1400, stepSize: 200, max: 2000, minorStep: 100 },
            "10": { target: 1200, stepSize: 200, max: 2000, minorStep: 100 },
            "11": { target: 900, stepSize: 100, max: 1000, minorStep: 50 },
            "12": { target: 250, stepSize: 50, max: 500, minorStep: 25 },
            "21": { target: 1000, stepSize: 100, max: 1500, minorStep: 50 },
            // สีคิ้ว
            "C1": { target: 3000, stepSize: 200, max: 3000, minorStep: 100 },
            "C2": { target: 1700, stepSize: 200, max: 2000, minorStep: 100 },
            "C3": { target: 3000, stepSize: 200, max: 3000, minorStep: 100 },
            "C4": { target: 3100, stepSize: 200, max: 3200, minorStep: 100 }
        };

        // เป้าหมายสะสมทั้งหมด (ตัน/วัน) และการตั้งค่าแกน Y
        const factoryConfigs = {
            kranburi: { target: 35000, stepSize: 2500, max: 40000, minorStep: 1250 },
            sikhio: { target: 12500, stepSize: 1000, max: 15000, minorStep: 500 }
        };

        // วันเริ่มต้นของแต่ละโรงงาน
        const startDates = {
            kranburi: { day: 7, month: 12 },  // 7 ธ.ค.
            sikhio: { day: 9, month: 12 }     // 9 ธ.ค.
        };

        // ตัวแปร global
        let currentMode = 'kranburi';
        let currentView = 'all';
        let currentZoneMode = 'kranburi';
        let selectedZone = null;
        let chartInstance = null;

        // อัพเดทวันที่ปัจจุบัน
        document.addEventListener('DOMContentLoaded', function() {
            updateCurrentDate();
        });

        // อัพเดทวันที่ปัจจุบัน
        function updateCurrentDate() {
            const now = new Date();
            const day = now.getDate();
            const month = now.getMonth() + 1;
            const year = now.getFullYear() + 543; // แปลงเป็น พ.ศ.
            document.querySelectorAll('.current-date').forEach(el => {
                el.textContent = `วันที่ ${day}/${month}/${year}`;
            });
        }

        // แสดงหน้าหลัก
        function showMainPage() {
            document.getElementById('mainContent').style.display = 'block';
            document.getElementById('reportContent').style.display = 'none';
            document.querySelector('.nav-menu a[href="#"]').classList.add('active');
            document.querySelectorAll('.nav-menu a').forEach((link, index) => {
                if (index !== 0) link.classList.remove('active');
            });
        }

        // แสดงหน้ารายงาน
        function showReportPage() {
            if (!uploadedFiles.kranburi || !uploadedFiles.sikhio || !uploadedFiles.farmers) {
                alert('กรุณาอัพโหลดไฟล์ข้อมูลครบทั้ง 3 ไฟล์ก่อนเข้าใช้งานหน้ารายงาน');
                return;
            }
            
            document.getElementById('mainContent').style.display = 'none';
            document.getElementById('reportContent').style.display = 'block';
            document.getElementById('dashboardSection').style.display = 'block';
            
            // อัพเดทเมนู
            document.querySelectorAll('.nav-menu a').forEach(link => {
                link.classList.remove('active');
            });
            document.querySelectorAll('.nav-menu a')[2].classList.add('active');
            
            // สร้างกราฟ
            generateChart();
        }

        // ฟังก์ชันจัดการอัพโหลดไฟล์
        async function handleFileUpload(input, fileType) {
            const file = input.files[0];
            
            if (!file) return;
            
            const fileId = getFileId(fileType);
            
            const validation = validateFile(file);
            if (!validation.valid) {
                alert(validation.message);
                resetFile(fileType);
                return;
            }
            
            showFileInfo(fileType, file);
            
            updateUploadArea(fileType, 'active');
            updateFileStatus(fileType, 'uploading', 'กำลังอัพโหลด...');
            
            simulateProgress(fileType);
            
            try {
                const fileData = await readCSVFile(file, fileType);
                
                uploadedFiles[fileType] = fileData;
                
                displaySampleData(fileType, fileData.data);
                
                updateSummaryCards();
                
                updateFileStatus(fileType, 'success', 'อัพโหลดสำเร็จ');
                updateUploadArea(fileType, 'success');
                
                checkAllFilesUploaded();
                
            } catch (error) {
                updateFileStatus(fileType, 'error', `ข้อผิดพลาด: ${error.message}`);
                updateUploadArea(fileType, 'error');
                console.error('Error reading file:', error);
            }
        }

        // ตรวจสอบไฟล์
        function validateFile(file) {
            const allowedTypes = ['text/csv', 'application/vnd.ms-excel'];
            const maxSize = 100 * 1024 * 1024;
            
            if (!allowedTypes.includes(file.type) && !file.name.toLowerCase().endsWith('.csv')) {
                return { valid: false, message: 'ไฟล์ต้องเป็นรูปแบบ .csv เท่านั้น' };
            }
            
            if (file.size > maxSize) {
                return { valid: false, message: 'ขนาดไฟล์ต้องไม่เกิน 100MB' };
            }
            
            return { valid: true, message: 'ไฟล์ถูกต้อง' };
        }

        // อ่านไฟล์ CSV
        function readCSVFile(file, fileType) {
            return new Promise((resolve, reject) => {
                const reader = new FileReader();
                
                reader.onload = function(e) {
                    try {
                        const content = e.target.result;
                        const lines = content.split('\n');
                        
                        let headers = [];
                        let data = [];
                        let totalWeight = 0;
                        
                        if (fileType === 'kranburi' || fileType === 'sikhio') {
                            if (lines.length <= 3) {
                                throw new Error('ไฟล์มีข้อมูลไม่ครบตามรูปแบบที่กำหนด');
                            }
                            
                            headers = lines[3].split(',').map(h => h.trim());
                            
                            let dataEnded = false;
                            for (let i = 5; i < lines.length; i++) {
                                const trimmedLine = lines[i].trim();
                                if (trimmedLine === '' || trimmedLine === null || trimmedLine === undefined) {
                                    dataEnded = true;
                                    continue;
                                }
                                
                                if (dataEnded) {
                                    break;
                                }
                                
                                const values = lines[i].split(',');
                                
                                let hasData = false;
                                for (let j = 0; j < values.length; j++) {
                                    if (values[j] && values[j].trim() !== '') {
                                        hasData = true;
                                        break;
                                    }
                                }
                                
                                if (!hasData) {
                                    dataEnded = true;
                                    continue;
                                }
                                
                                const row = {};
                                
                                headers.forEach((header, index) => {
                                    row[header] = values[index] ? values[index].trim() : '';
                                });
                                
                                data.push(row);
                                
                                if (row['น.น.สุทธิ'] && !isNaN(parseFloat(row['น.น.สุทธิ']))) {
                                    totalWeight += parseFloat(row['น.น.สุทธิ']);
                                }
                            }
                        } else if (fileType === 'farmers') {
                            if (lines.length <= 0) {
                                throw new Error('ไฟล์มีข้อมูลไม่ครบตามรูปแบบที่กำหนด');
                            }
                            
                            headers = lines[0].split(',').map(h => h.trim());
                            
                            let dataEnded = false;
                            for (let i = 1; i < lines.length; i++) {
                                const trimmedLine = lines[i].trim();
                                if (trimmedLine === '' || trimmedLine === null || trimmedLine === undefined) {
                                    dataEnded = true;
                                    continue;
                                }
                                
                                if (dataEnded) {
                                    break;
                                }
                                
                                const values = lines[i].split(',');
                                
                                let hasData = false;
                                for (let j = 0; j < values.length; j++) {
                                    if (values[j] && values[j].trim() !== '') {
                                        hasData = true;
                                        break;
                                    }
                                }
                                
                                if (!hasData) {
                                    dataEnded = true;
                                    continue;
                                }
                                
                                const row = {};
                                
                                headers.forEach((header, index) => {
                                    row[header] = values[index] ? values[index].trim() : '';
                                });
                                
                                data.push(row);
                            }
                        }
                        
                        resolve({
                            headers: headers,
                            data: data.slice(0, 5),
                            rawData: data,
                            totalRows: data.length,
                            totalWeight: totalWeight,
                            fileName: file.name,
                            fileType: fileType
                        });
                    } catch (error) {
                        reject(error);
                    }
                };
                
                reader.onerror = reject;
                reader.readAsText(file, 'TIS-620');
            });
        }

        // แสดงข้อมูลไฟล์
        function showFileInfo(fileType, file) {
            const fileId = getFileId(fileType);
            document.getElementById(`fileStatus${fileId}`).style.display = 'block';
            document.getElementById(`fileName${fileId}`).textContent = file.name;
            document.getElementById(`fileSize${fileId}`).textContent = formatFileSize(file.size);
        }

        // สร้าง progress bar แบบสมมติ
        function simulateProgress(fileType) {
            const fileId = getFileId(fileType);
            const progressBar = document.getElementById(`progress${fileId}`);
            let width = 0;
            
            const interval = setInterval(() => {
                if (width >= 100) {
                    clearInterval(interval);
                } else {
                    width += 10;
                    progressBar.style.width = width + '%';
                }
            }, 100);
        }

        // แสดงตัวอย่างข้อมูล
        function displaySampleData(fileType, sampleData) {
            const tableBody = document.getElementById('tableBody');
            
            tableBody.innerHTML = '';
            
            let hasData = false;
            
            Object.keys(uploadedFiles).forEach(key => {
                const file = uploadedFiles[key];
                if (file && file.data && file.data.length > 0) {
                    hasData = true;
                    const row = document.createElement('tr');
                    
                    const fileNameCell = document.createElement('td');
                    fileNameCell.style.width = '200px';
                    fileNameCell.innerHTML = `<strong>${getFileName(key)}</strong><br><small>${file.fileName}</small>`;
                    row.appendChild(fileNameCell);
                    
                    const sampleCell = document.createElement('td');
                    
                    let sampleHTML = '<div style="overflow-x: auto;"><table style="width: 100%; font-size: 0.9rem;">';
                    
                    sampleHTML += '<thead><tr>';
                    file.headers.forEach(header => {
                        sampleHTML += `<th style="padding: 5px; background-color: #f0f0f0;">${header}</th>`;
                    });
                    sampleHTML += '</tr></thead>';
                    
                    sampleHTML += '<tbody>';
                    file.data.forEach(rowData => {
                        sampleHTML += '<tr>';
                        file.headers.forEach(header => {
                            sampleHTML += `<td style="padding: 5px; border-bottom: 1px solid #eee;">${rowData[header] || ''}</td>`;
                        });
                        sampleHTML += '</tr>';
                    });
                    sampleHTML += '</tbody></table></div>';
                    
                    sampleCell.innerHTML = sampleHTML;
                    row.appendChild(sampleCell);
                    
                    tableBody.appendChild(row);
                }
            });
            
            if (!hasData) {
                tableBody.innerHTML = `
                    <tr>
                        <td colspan="2" class="no-data">ยังไม่มีข้อมูล กรุณาอัพโหลดไฟล์</td>
                    </tr>
                `;
            }
        }

        // อัพเดท summary cards
        function updateSummaryCards() {
            let fileCount = 0;
            let totalRows = 0;
            let totalWeight = 0;
            let percentageTarget = 0;
            
            Object.keys(uploadedFiles).forEach(key => {
                if (uploadedFiles[key]) {
                    fileCount++;
                    totalRows += uploadedFiles[key].totalRows || 0;
                    
                    if (key === 'kranburi' || key === 'sikhio') {
                        totalWeight += uploadedFiles[key].totalWeight || 0;
                    }
                }
            });
            
            if (totalWeight > 0) {
                percentageTarget = ((totalWeight / 2400000) * 100).toFixed(2);
            }
            
            document.getElementById('fileCount').textContent = `${fileCount}/3`;
            document.getElementById('totalRows').textContent = totalRows.toLocaleString();
            document.getElementById('totalWeight').textContent = totalWeight.toFixed(2);
            document.getElementById('percentageTarget').textContent = `${percentageTarget}%`;
        }

        // ตรวจสอบว่าอัพโหลดครบทุกไฟล์หรือไม่
        function checkAllFilesUploaded() {
            const fileCount = Object.keys(uploadedFiles).filter(key => uploadedFiles[key]).length;
            
            if (fileCount === 3) {
                document.getElementById('validateBtn').disabled = false;
                document.getElementById('generateReportBtn').disabled = false;
            }
        }

        // ตรวจสอบข้อมูลทั้งหมด
        async function validateAllFiles() {
            const fileCount = Object.keys(uploadedFiles).filter(key => uploadedFiles[key]).length;
            if (fileCount < 3) {
                alert('กรุณาอัพโหลดไฟล์ครบทั้ง 3 ไฟล์ก่อนตรวจสอบข้อมูล');
                return;
            }
            
            document.getElementById('validateBtn').innerHTML = '<div class="loading"></div> กำลังตรวจสอบ...';
            document.getElementById('validateBtn').disabled = true;
            
            const validationResults = [];
            
            for (const [fileType, fileData] of Object.entries(uploadedFiles)) {
                if (fileData) {
                    const validation = validateFileData(fileType, fileData);
                    validationResults.push(validation);
                    
                    updateValidationStatus(fileType, validation);
                }
            }
            
            displayValidationResults(validationResults);
            
            const allValid = validationResults.every(r => r.isValid);
            
            document.getElementById('validateBtn').innerHTML = '<i class="fas fa-search"></i> ตรวจสอบข้อมูล';
            document.getElementById('validateBtn').disabled = false;
            
            if (allValid) {
                document.getElementById('downloadBtn').disabled = false;
                alert('การตรวจสอบข้อมูลเสร็จสิ้น\nข้อมูลทั้งหมดถูกต้องและพร้อมสร้างรายงาน');
            } else {
                alert('พบข้อผิดพลาดในข้อมูล กรุณาตรวจสอบไฟล์อีกครั้ง');
            }
        }

        // ตรวจสอบข้อมูลไฟล์
        function validateFileData(fileType, fileData) {
            const requiredColumns = ['น.น.สุทธิ'];
            const missingColumns = [];
            const dataErrors = [];
            
            if (fileType === 'kranburi' || fileType === 'sikhio') {
                requiredColumns.forEach(column => {
                    if (!fileData.headers.includes(column)) {
                        missingColumns.push(column);
                    }
                });
            }
            
            if (missingColumns.length === 0 && (fileType === 'kranburi' || fileType === 'sikhio')) {
                fileData.rawData.forEach((row, index) => {
                    const rowNum = index + 6;
                    
                    if (!row['น.น.สุทธิ'] || isNaN(parseFloat(row['น.น.สุทธิ'])) || parseFloat(row['น.น.สุทธิ']) < 0) {
                        dataErrors.push(`แถว ${rowNum}: ค่าน้ำหนักสุทธิไม่ถูกต้อง`);
                    }
                });
            }
            
            return {
                fileType: fileType,
                fileName: getFileName(fileType),
                isValid: missingColumns.length === 0 && dataErrors.length === 0,
                missingColumns: missingColumns,
                dataErrors: dataErrors,
                totalRows: fileData.totalRows,
                message: missingColumns.length > 0 
                    ? `ขาดคอลัมน์: ${missingColumns.join(', ')}`
                    : dataErrors.length > 0
                    ? `พบ ${dataErrors.length} ข้อผิดพลาด`
                    : 'ข้อมูลถูกต้อง'
            };
        }

        // แสดงผลการตรวจสอบ
        function displayValidationResults(results) {
            const validationResults = document.getElementById('validationResults');
            const validationSummary = document.getElementById('validationSummary');
            
            validationResults.innerHTML = '';
            
            results.forEach(result => {
                const li = document.createElement('li');
                
                if (result.isValid) {
                    li.innerHTML = `<i class="fas fa-check-circle success"></i> 
                                   <strong>${result.fileName}</strong>: ข้อมูลถูกต้อง (${result.totalRows} แถว)`;
                } else if (result.missingColumns.length > 0) {
                    li.innerHTML = `<i class="fas fa-exclamation-circle error"></i> 
                                   <strong>${result.fileName}</strong>: ${result.message}`;
                } else {
                    li.innerHTML = `<i class="fas fa-exclamation-triangle warning"></i> 
                                   <strong>${result.fileName}</strong>: ${result.message}`;
                    
                    if (result.dataErrors.length > 0) {
                        const errorList = document.createElement('ul');
                        errorList.style.marginLeft = '20px';
                        errorList.style.marginTop = '5px';
                        errorList.style.fontSize = '0.9rem';
                        
                        const errorsToShow = result.dataErrors.slice(0, 3);
                        errorsToShow.forEach(error => {
                            const errorItem = document.createElement('li');
                            errorItem.textContent = error;
                            errorList.appendChild(errorItem);
                        });
                        
                        if (result.dataErrors.length > 3) {
                            const moreItem = document.createElement('li');
                            moreItem.textContent = `... และอีก ${result.dataErrors.length - 3} ข้อผิดพลาด`;
                            errorList.appendChild(moreItem);
                        }
                        
                        li.appendChild(errorList);
                    }
                }
                
                validationResults.appendChild(li);
            });
            
            validationSummary.style.display = 'block';
        }

        // สร้างรายงาน
        function generateReport() {
            if (!uploadedFiles.kranburi || !uploadedFiles.sikhio || !uploadedFiles.farmers) {
                alert('กรุณาอัพโหลดไฟล์ข้อมูลครบทั้ง 3 ไฟล์ก่อนสร้างรายงาน');
                return;
            }
            
            showReportPage();
        }

        // เลือกโหมด (ครบุรี/สีคิ้ว)
        function selectMode(mode) {
            currentMode = mode;
            
            document.querySelectorAll('#allViewControls .mode-btn').forEach(btn => {
                btn.classList.remove('active');
            });
            event.target.classList.add('active');
            
            generateChart();
        }

        // เลือกโหมดสำหรับรายเขต
        function selectZoneMode(mode) {
            currentZoneMode = mode;
            selectedZone = null;
            
            document.querySelectorAll('#zoneViewControls .mode-btn').forEach(btn => {
                btn.classList.remove('active');
            });
            event.target.classList.add('active');
            
            showZoneButtons();
            generateChart();
        }

        // เลือกมุมมอง (ทั้งหมด/แบ่งเขต)
        function selectView(view) {
            currentView = view;
            
            document.querySelectorAll('.view-btn').forEach(btn => {
                btn.classList.remove('active');
            });
            event.target.classList.add('active');
            
            if (view === 'all') {
                document.getElementById('allViewControls').style.display = 'flex';
                document.getElementById('zoneViewControls').style.display = 'none';
                currentMode = 'kranburi';
                selectedZone = null;
                document.querySelectorAll('#allViewControls .mode-btn').forEach(btn => {
                    btn.classList.remove('active');
                });
                document.querySelectorAll('#allViewControls .mode-btn')[0].classList.add('active');
            } else {
                document.getElementById('allViewControls').style.display = 'none';
                document.getElementById('zoneViewControls').style.display = 'flex';
                currentZoneMode = 'kranburi';
                showZoneButtons();
                document.querySelectorAll('#zoneViewControls .mode-btn').forEach(btn => {
                    btn.classList.remove('active');
                });
                document.querySelectorAll('#zoneViewControls .mode-btn')[0].classList.add('active');
            }
            
            generateChart();
        }

        // แสดงปุ่มเลือกเขต
        function showZoneButtons() {
            const zoneButtons = document.getElementById('zoneButtons');
            zoneButtons.innerHTML = '';
            
            const zoneList = zones[currentZoneMode];
            
            zoneList.forEach(zone => {
                const button = document.createElement('button');
                button.className = 'view-btn';
                button.textContent = `เขต ${zone}`;
                button.style.margin = '2px';
                button.style.padding = '5px 10px';
                button.style.fontSize = '0.9rem';
                
                if (selectedZone === zone) {
                    button.classList.add('active');
                }
                
                button.onclick = function() {
                    selectZone(zone);
                };
                
                zoneButtons.appendChild(button);
            });
            
            if (zoneList.length > 0 && !selectedZone) {
                selectedZone = zoneList[0];
                document.querySelectorAll('#zoneButtons .view-btn')[0].classList.add('active');
            }
        }

        // เลือกเขต
        function selectZone(zone) {
            selectedZone = zone;
            
            document.querySelectorAll('#zoneButtons .view-btn').forEach(btn => {
                btn.classList.remove('active');
            });
            event.target.classList.add('active');
            
            generateChart();
        }

        // สร้างกราฟ
        function generateChart() {
            if (!uploadedFiles.kranburi || !uploadedFiles.sikhio || !uploadedFiles.farmers) {
                alert('กรุณาอัพโหลดไฟล์ข้อมูลครบทั้ง 3 ไฟล์ก่อนสร้างกราฟ');
                return;
            }
            
            let processedData;
            if (currentView === 'all') {
                processedData = processDataForAllView(currentMode);
            } else {
                if (!selectedZone) {
                    alert('กรุณาเลือกเขตที่ต้องการดูรายงาน');
                    return;
                }
                processedData = processDataForZoneView(currentZoneMode, selectedZone);
            }
            
            updateDashboardSummary(processedData);
            createZoneLegend();
            updateChartTitle(processedData);
            
            if (chartInstance) {
                chartInstance.destroy();
            }
            
            const ctx = document.getElementById('sugarChart').getContext('2d');
            const chartData = prepareChartData(processedData);
            
            let config;
            if (currentView === 'all') {
                config = createAllViewConfig(chartData, processedData);
            } else {
                config = createZoneViewConfig(chartData, processedData);
            }
            
            chartInstance = new Chart(ctx, config);
        }

        // ประมวลผลข้อมูลสำหรับมุมมองทั้งหมด
        function processDataForAllView(mode) {
            const sugarData = uploadedFiles[mode];
            
            if (!sugarData) {
                return { dailyWeights: {}, accumulatedWeights: {}, byZone: {} };
            }
            
            const dailyWeights = {};
            
            sugarData.rawData.forEach(row => {
                const dateStr = parseDateColumn(row['ชั่งออก']);
                if (!dateStr) return;
                
                const weight = parseFloat(row['น.น.สุทธิ']) || 0;
                
                if (!dailyWeights[dateStr]) {
                    dailyWeights[dateStr] = 0;
                }
                dailyWeights[dateStr] += weight;
            });
            
            const dateRange = generateDateRange(mode);
            
            const accumulatedWeights = {};
            let accumulated = 0;
            
            dateRange.forEach(date => {
                const dailyWeight = dailyWeights[date] || 0;
                accumulated += dailyWeight;
                accumulatedWeights[date] = accumulated;
            });
            
            const totalAccumulatedWeight = Object.values(dailyWeights).reduce((a, b) => a + b, 0);
            
            const factoryName = mode === 'kranburi' ? 'ครบุรี' : 'สีคิ้ว';
            const factoryConfig = factoryConfigs[mode];
            const startDate = startDates[mode];
            const startDateStr = `${startDate.day}/${startDate.month}/68`;
            const now = new Date();
            const currentDateStr = `${now.getDate()}/${now.getMonth() + 1}/${(now.getFullYear() + 543).toString().slice(-2)}`;
            
            return {
                dailyWeights: dailyWeights,
                accumulatedWeights: accumulatedWeights,
                totalWeight: totalAccumulatedWeight,
                dateRange: dateRange,
                factoryName: factoryName,
                factoryConfig: factoryConfig,
                startDate: startDateStr,
                currentDate: currentDateStr,
                mode: mode
            };
        }

        // ประมวลผลข้อมูลสำหรับมุมมองรายเขต
        function processDataForZoneView(mode, zone) {
            const sugarData = uploadedFiles[mode];
            const farmerData = uploadedFiles.farmers;
            
            if (!sugarData || !farmerData) {
                return { dailyWeights: {}, accumulatedWeights: {}, byZone: {} };
            }
            
            // สร้าง mapping ระหว่าง ong Address กับเขตจากไฟล์ฐานข้อมูลชาวไร่
            const addressToZoneMap = {};
            farmerData.rawData.forEach(farmer => {
                if (farmer['ong Address'] && farmer['เขต']) {
                    addressToZoneMap[farmer['ong Address']] = farmer['เขต'];
                }
            });
            
            const dailyWeights = {};
            
            // ประมวลผลข้อมูลน้ำหนักเฉพาะเขตที่เลือก
            sugarData.rawData.forEach(row => {
                const dateStr = parseDateColumn(row['ชั่งออก']);
                if (!dateStr) return;
                
                const quota = row['โควตา'] || '';
                if (quota && addressToZoneMap[quota] === zone) {
                    const weight = parseFloat(row['น.น.สุทธิ']) || 0;
                    
                    if (!dailyWeights[dateStr]) {
                        dailyWeights[dateStr] = 0;
                    }
                    dailyWeights[dateStr] += weight;
                }
            });
            
            const dateRange = generateDateRange(mode);
            
            const accumulatedWeights = {};
            let accumulated = 0;
            
            dateRange.forEach(date => {
                const dailyWeight = dailyWeights[date] || 0;
                accumulated += dailyWeight;
                accumulatedWeights[date] = accumulated;
            });
            
            const totalAccumulatedWeight = Object.values(dailyWeights).reduce((a, b) => a + b, 0);
            
            const factoryName = mode === 'kranburi' ? 'ครบุรี' : 'สีคิ้ว';
            const zoneConfig = zoneConfigs[zone];
            const startDate = startDates[mode];
            const startDateStr = `${startDate.day}/${startDate.month}/68`;
            const now = new Date();
            const currentDateStr = `${now.getDate()}/${now.getMonth() + 1}/${(now.getFullYear() + 543).toString().slice(-2)}`;
            
            return {
                dailyWeights: dailyWeights,
                accumulatedWeights: accumulatedWeights,
                totalWeight: totalAccumulatedWeight,
                zone: zone,
                zoneConfig: zoneConfig,
                dateRange: dateRange,
                factoryName: factoryName,
                startDate: startDateStr,
                currentDate: currentDateStr,
                mode: mode
            };
        }

        // สร้างช่วงวันที่
        function generateDateRange(mode) {
            const dateRange = [];
            
            const startDate = startDates[mode];
            const now = new Date();
            const currentDay = now.getDate();
            const currentMonth = now.getMonth() + 1;
            const currentYear = 69; // 2569
            
            // ถ้าเป็นเดือนธันวาคม 68
            if (startDate.month === 12) {
                for (let day = startDate.day; day <= 31; day++) {
                    dateRange.push(`${day}/12`);
                }
            }
            
            // เพิ่มวันในเดือนมกราคม 69
            for (let day = 1; day <= currentDay; day++) {
                dateRange.push(`${day}/01`);
            }
            
            return dateRange;
        }

        // เตรียมข้อมูลสำหรับกราฟ
        function prepareChartData(processedData) {
            const dateRange = processedData.dateRange;
            
            if (currentView === 'all') {
                return {
                    labels: dateRange.map(date => formatDateForChart(date)),
                    datasets: [
                        // Dataset 0: แท่งเป้าหมาย (พื้นหลัง)
                        {
                            label: 'เป้าหมายรายวัน',
                            data: dateRange.map(() => processedData.factoryConfig.target),
                            backgroundColor: 'rgba(255, 152, 0, 0.1)',
                            borderColor: 'rgba(255, 152, 0, 0.3)',
                            borderWidth: 0,
                            barPercentage: 1.0,
                            categoryPercentage: 1.0,
                            order: 1
                        },
                        // Dataset 1: น้ำหนักรายวัน
                        {
                            label: 'น้ำหนักรายวัน',
                            data: dateRange.map(date => (processedData.dailyWeights[date] || 0)),
                            backgroundColor: getChartColor(processedData.mode, false),
                            borderColor: getChartColor(processedData.mode, true),
                            borderWidth: 1,
                            hoverBackgroundColor: getChartColor(processedData.mode, false, true),
                            hoverBorderColor: getChartColor(processedData.mode, true, true),
                            hoverBorderWidth: 2,
                            order: 2
                        },
                        // Dataset 2: น้ำหนักสะสม (เส้น)
                        {
                            type: 'line',
                            label: 'ตันสะสม',
                            data: dateRange.map(date => (processedData.accumulatedWeights[date] || 0)),
                            backgroundColor: 'rgba(156, 39, 176, 0.1)',
                            borderColor: '#9C27B0',
                            borderWidth: 2,
                            pointRadius: 0,
                            tension: 0.1,
                            fill: false,
                            yAxisID: 'y-accumulated',
                            order: 3
                        }
                    ]
                };
            } else {
                return {
                    labels: dateRange.map(date => formatDateForChart(date)),
                    datasets: [
                        // Dataset 0: แท่งเป้าหมาย (พื้นหลัง)
                        {
                            label: 'เป้าหมายรายวัน',
                            data: dateRange.map(() => processedData.zoneConfig.target),
                            backgroundColor: 'rgba(255, 152, 0, 0.1)',
                            borderColor: 'rgba(255, 152, 0, 0.3)',
                            borderWidth: 0,
                            barPercentage: 1.0,
                            categoryPercentage: 1.0,
                            order: 1
                        },
                        // Dataset 1: น้ำหนักรายวัน
                        {
                            label: `เขต ${processedData.zone} - น้ำหนักรายวัน`,
                            data: dateRange.map(date => (processedData.dailyWeights[date] || 0)),
                            backgroundColor: getChartColor(processedData.mode, false),
                            borderColor: getChartColor(processedData.mode, true),
                            borderWidth: 1,
                            hoverBackgroundColor: getChartColor(processedData.mode, false, true),
                            hoverBorderColor: getChartColor(processedData.mode, true, true),
                            hoverBorderWidth: 2,
                            order: 2
                        },
                        // Dataset 2: น้ำหนักสะสม (เส้น)
                        {
                            type: 'line',
                            label: 'ตันสะสม',
                            data: dateRange.map(date => (processedData.accumulatedWeights[date] || 0)),
                            backgroundColor: 'rgba(156, 39, 176, 0.1)',
                            borderColor: '#9C27B0',
                            borderWidth: 2,
                            pointRadius: 0,
                            tension: 0.1,
                            fill: false,
                            yAxisID: 'y-accumulated',
                            order: 3
                        }
                    ]
                };
            }
        }

        // ฟังก์ชันเลือกสีตามโหมด
        function getChartColor(mode, isBorder = false, isHover = false) {
            if (mode === 'kranburi') {
                // ครบุรี: โทนสีฟ้า
                if (isBorder) {
                    return isHover ? '#1976D2' : '#2196F3';
                } else {
                    return isHover ? '#64B5F6' : '#90CAF9';
                }
            } else {
                // สีคิ้ว: โทนสีเขียว
                if (isBorder) {
                    return isHover ? '#1B5E20' : '#2E7D32';
                } else {
                    return isHover ? '#4CAF50' : '#81C784';
                }
            }
        }

        // สร้างการตั้งค่ากราฟสำหรับมุมมองทั้งหมด
        function createAllViewConfig(chartData, processedData) {
            const dateRange = processedData.dateRange;
            const factoryConfig = processedData.factoryConfig;
            const maxDailyWeight = Math.max(...Object.values(processedData.dailyWeights).filter(val => val !== undefined));
            const maxAccumulated = Math.max(...Object.values(processedData.accumulatedWeights).filter(val => val !== undefined));
            
            // คำนวณค่า max สำหรับแกน Y ซ้าย (ตันรายวัน)
            let yLeftMax = factoryConfig.max;
            if (maxDailyWeight > factoryConfig.target) {
                yLeftMax = Math.ceil(maxDailyWeight / factoryConfig.stepSize) * factoryConfig.stepSize;
            }
            
            // คำนวณค่า max สำหรับแกน Y ขวา (ตันสะสม)
            let yRightMax = 2500000; // 2,500,000 ตัน
            if (maxAccumulated > yRightMax) {
                yRightMax = Math.ceil(maxAccumulated / 100000) * 100000;
            }
            
            return {
                type: 'bar',
                data: chartData,
                options: {
                    responsive: true,
                    maintainAspectRatio: false,
                    scales: {
                        // แกน Y ซ้าย: ตันรายวัน
                        y: {
                            type: 'linear',
                            position: 'left',
                            title: {
                                display: true,
                                text: 'ตันรายวัน',
                                font: {
                                    size: 14,
                                    weight: 'bold'
                                }
                            },
                            min: 0,
                            max: yLeftMax,
                            ticks: {
                                stepSize: factoryConfig.stepSize,
                                callback: function(value) {
                                    return value.toLocaleString();
                                },
                                font: {
                                    size: 12
                                }
                            },
                            grid: {
                                drawTicks: false,
                                color: function(context) {
                                    // สร้างขีดเล็กทุก minorStep
                                    if (context.tick.value % factoryConfig.minorStep === 0 && context.tick.value % factoryConfig.stepSize !== 0) {
                                        return 'rgba(0, 0, 0, 0.1)';
                                    }
                                    return 'rgba(0, 0, 0, 0.05)'; // ลดความเข้มของเส้นกริด
                                }
                            }
                        },
                        // แกน Y ขวา: ตันสะสม
                        'y-accumulated': {
                            type: 'linear',
                            position: 'right',
                            title: {
                                display: true,
                                text: 'ตันสะสม',
                                font: {
                                    size: 14,
                                    weight: 'bold'
                                }
                            },
                            min: 0,
                            max: yRightMax,
                            ticks: {
                                stepSize: 100000,
                                callback: function(value) {
                                    return (value / 1000).toFixed(0) + 'K';
                                },
                                font: {
                                    size: 12
                                }
                            },
                            grid: {
                                drawOnChartArea: false, // ไม่วาดกริดบนพื้นที่กราฟ
                            }
                        },
                        x: {
                            title: {
                                display: true,
                                text: 'วันที่',
                                font: {
                                    size: 14,
                                    weight: 'bold'
                                }
                            },
                            ticks: {
                                font: {
                                    size: 11
                                },
                                maxTicksLimit: dateRange.length,
                                callback: function(value, index, values) {
                                    return dateRange[index];
                                }
                            },
                            grid: {
                                display: false // ลบเส้นกริดแนวตั้ง
                            }
                        }
                    },
                    plugins: {
                        legend: {
                            display: true,
                            position: 'top',
                            labels: {
                                boxWidth: 12,
                                padding: 10,
                                font: {
                                    size: 12
                                }
                            }
                        },
                        tooltip: {
                            callbacks: {
                                label: function(context) {
                                    let label = context.dataset.label || '';
                                    if (label) {
                                        label += ': ';
                                    }
                                    
                                    let value = context.parsed.y;
                                    
                                    // แสดงหน่วยที่ถูกต้องตาม dataset
                                    if (context.datasetIndex === 0) {
                                        label += `เป้าหมาย ${value.toLocaleString()} ตัน`;
                                    } else if (context.datasetIndex === 1) {
                                        label += `น้ำหนักรายวัน ${value.toLocaleString()} ตัน`;
                                    } else if (context.datasetIndex === 2) {
                                        label += `ตันสะสม ${value.toLocaleString()} ตัน`;
                                    }
                                    
                                    return label;
                                }
                            },
                            backgroundColor: 'rgba(0, 0, 0, 0.8)',
                            titleFont: {
                                size: 14
                            },
                            bodyFont: {
                                size: 13
                            }
                        }
                    },
                    interaction: {
                        intersect: false,
                        mode: 'index'
                    },
                    hover: {
                        mode: 'index',
                        intersect: false
                    },
                    animation: {
                        duration: 1000,
                        easing: 'easeOutQuart'
                    }
                }
            };
        }

        // สร้างการตั้งค่ากราฟสำหรับมุมมองรายเขต
        function createZoneViewConfig(chartData, processedData) {
            const dateRange = processedData.dateRange;
            const zoneConfig = processedData.zoneConfig;
            const maxDailyWeight = Math.max(...Object.values(processedData.dailyWeights).filter(val => val !== undefined));
            const maxAccumulated = Math.max(...Object.values(processedData.accumulatedWeights).filter(val => val !== undefined));
            
            // คำนวณค่า max สำหรับแกน Y ซ้าย (ตันรายวัน)
            let yLeftMax = zoneConfig.max;
            if (maxDailyWeight > zoneConfig.target) {
                yLeftMax = Math.ceil(maxDailyWeight / zoneConfig.stepSize) * zoneConfig.stepSize;
            }
            
            // คำนวณค่า max สำหรับแกน Y ขวา (ตันสะสม)
            let yRightMax = 2500000; // 2,500,000 ตัน
            if (maxAccumulated > yRightMax) {
                yRightMax = Math.ceil(maxAccumulated / 100000) * 100000;
            }
            
            return {
                type: 'bar',
                data: chartData,
                options: {
                    responsive: true,
                    maintainAspectRatio: false,
                    scales: {
                        // แกน Y ซ้าย: ตันรายวัน
                        y: {
                            type: 'linear',
                            position: 'left',
                            title: {
                                display: true,
                                text: 'ตันรายวัน',
                                font: {
                                    size: 14,
                                    weight: 'bold'
                                }
                            },
                            min: 0,
                            max: yLeftMax,
                            ticks: {
                                stepSize: zoneConfig.stepSize,
                                callback: function(value) {
                                    return value.toLocaleString();
                                },
                                font: {
                                    size: 12
                                }
                            },
                            grid: {
                                drawTicks: false,
                                color: function(context) {
                                    // สร้างขีดเล็กทุก minorStep
                                    if (context.tick.value % zoneConfig.minorStep === 0 && context.tick.value % zoneConfig.stepSize !== 0) {
                                        return 'rgba(0, 0, 0, 0.1)';
                                    }
                                    return 'rgba(0, 0, 0, 0.05)'; // ลดความเข้มของเส้นกริด
                                }
                            }
                        },
                        // แกน Y ขวา: ตันสะสม
                        'y-accumulated': {
                            type: 'linear',
                            position: 'right',
                            title: {
                                display: true,
                                text: 'ตันสะสม',
                                font: {
                                    size: 14,
                                    weight: 'bold'
                                }
                            },
                            min: 0,
                            max: yRightMax,
                            ticks: {
                                stepSize: 100000,
                                callback: function(value) {
                                    return (value / 1000).toFixed(0) + 'K';
                                },
                                font: {
                                    size: 12
                                }
                            },
                            grid: {
                                drawOnChartArea: false, // ไม่วาดกริดบนพื้นที่กราฟ
                            }
                        },
                        x: {
                            title: {
                                display: true,
                                text: 'วันที่',
                                font: {
                                    size: 14,
                                    weight: 'bold'
                                }
                            },
                            ticks: {
                                font: {
                                    size: 11
                                },
                                maxTicksLimit: dateRange.length,
                                callback: function(value, index, values) {
                                    return dateRange[index];
                                }
                            },
                            grid: {
                                display: false // ลบเส้นกริดแนวตั้ง
                            }
                        }
                    },
                    plugins: {
                        legend: {
                            display: true,
                            position: 'top',
                            labels: {
                                boxWidth: 12,
                                padding: 10,
                                font: {
                                    size: 12
                                }
                            }
                        },
                        tooltip: {
                            callbacks: {
                                label: function(context) {
                                    let label = context.dataset.label || '';
                                    if (label) {
                                        label += ': ';
                                    }
                                    
                                    let value = context.parsed.y;
                                    
                                    // แสดงหน่วยที่ถูกต้องตาม dataset
                                    if (context.datasetIndex === 0) {
                                        label += `เป้าหมาย ${value.toLocaleString()} ตัน`;
                                    } else if (context.datasetIndex === 1) {
                                        label += `น้ำหนักรายวัน ${value.toLocaleString()} ตัน`;
                                    } else if (context.datasetIndex === 2) {
                                        label += `ตันสะสม ${value.toLocaleString()} ตัน`;
                                    }
                                    
                                    return label;
                                }
                            },
                            backgroundColor: 'rgba(0, 0, 0, 0.8)',
                            titleFont: {
                                size: 14
                            },
                            bodyFont: {
                                size: 13
                            }
                        }
                    },
                    interaction: {
                        intersect: false,
                        mode: 'index'
                    },
                    hover: {
                        mode: 'index',
                        intersect: false
                    },
                    animation: {
                        duration: 1000,
                        easing: 'easeOutQuart'
                    }
                }
            };
        }

        // อัพเดทสรุปข้อมูลใน Dashboard
        function updateDashboardSummary(processedData) {
            const totalWeightInTons = processedData.totalWeight || 0;
            document.getElementById('totalWeightDashboard').textContent = Math.round(totalWeightInTons).toLocaleString();
        }

        // อัพเดทหัวข้อกราฟ
        function updateChartTitle(processedData) {
            const chartTitleArea = document.getElementById('chartTitleArea');
            const chartSubtitle = document.getElementById('chartSubtitle');
            const chartDate = document.getElementById('chartDate');
            
            chartTitleArea.style.display = 'block';
            
            if (currentView === 'all') {
                chartSubtitle.textContent = `โรงงาน${processedData.factoryName}`;
                chartDate.textContent = `วันที่ ${processedData.startDate} - ${processedData.currentDate}`;
            } else {
                chartSubtitle.textContent = `โรงงาน${processedData.factoryName} ประจำเขต ${processedData.zone}`;
                chartDate.textContent = `วันที่ ${processedData.startDate} - ${processedData.currentDate}`;
            }
        }

        // สร้าง legend สำหรับเขต
        function createZoneLegend() {
            const zoneLegend = document.getElementById('zoneLegend');
            
            if (currentView === 'byZone' && selectedZone) {
                const zoneColor = getChartColor(currentZoneMode, false);
                const targetValue = currentView === 'all' ? factoryConfigs[currentMode].target : zoneConfigs[selectedZone].target;
                
                let legendHTML = '';
                legendHTML += `
                    <div class="legend-item">
                        <div class="legend-color" style="background-color: ${zoneColor}"></div>
                        <span>น้ำหนักรายวัน</span>
                    </div>
                    <div class="legend-item">
                        <div class="legend-color" style="background-color: rgba(255, 152, 0, 0.3)"></div>
                        <span>เป้าหมาย: ${targetValue.toLocaleString()} ตัน/วัน</span>
                    </div>
                    <div class="legend-item">
                        <div class="legend-color" style="background-color: #9C27B0"></div>
                        <span>ตันสะสม</span>
                    </div>
                `;
                
                zoneLegend.innerHTML = legendHTML;
                zoneLegend.style.display = 'flex';
            } else if (currentView === 'all') {
                const modeColor = getChartColor(currentMode, false);
                const targetValue = factoryConfigs[currentMode].target;
                
                let legendHTML = '';
                legendHTML += `
                    <div class="legend-item">
                        <div class="legend-color" style="background-color: ${modeColor}"></div>
                        <span>น้ำหนักรายวัน</span>
                    </div>
                    <div class="legend-item">
                        <div class="legend-color" style="background-color: rgba(255, 152, 0, 0.3)"></div>
                        <span>เป้าหมาย: ${targetValue.toLocaleString()} ตัน/วัน</span>
                    </div>
                    <div class="legend-item">
                        <div class="legend-color" style="background-color: #9C27B0"></div>
                        <span>ตันสะสม</span>
                    </div>
                `;
                
                zoneLegend.innerHTML = legendHTML;
                zoneLegend.style.display = 'flex';
            } else {
                zoneLegend.style.display = 'none';
            }
        }

        // บันทึกรูปภาพกราฟ
        function saveChartAsImage() {
            if (!chartInstance) {
                alert('กรุณาสร้างกราฟก่อนบันทึกรายงาน');
                return;
            }
            
            // สร้าง canvas ใหม่สำหรับรวมหัวข้อและกราฟ
            const chartCanvas = document.getElementById('sugarChart');
            const titleArea = document.getElementById('chartTitleArea');
            
            // สร้าง canvas ชั่วคราว
            const tempCanvas = document.createElement('canvas');
            const ctx = tempCanvas.getContext('2d');
            
            // ตั้งค่าขนาด canvas
            tempCanvas.width = chartCanvas.width;
            tempCanvas.height = chartCanvas.height + 150; // เพิ่มพื้นที่สำหรับหัวข้อ
            
            // วาดพื้นหลังสีขาว
            ctx.fillStyle = 'white';
            ctx.fillRect(0, 0, tempCanvas.width, tempCanvas.height);
            
            // วาดหัวข้อ
            ctx.fillStyle = '#2E7D32';
            ctx.font = 'bold 28px Sarabun';
            ctx.textAlign = 'center';
            ctx.fillText('รายงานอ้อยเข้าหีบ ปี 68/69', tempCanvas.width / 2, 40);
            
            // วาดหัวข้อย่อย
            ctx.fillStyle = '#343a40';
            ctx.font = 'bold 20px Sarabun';
            
            let subtitleText = '';
            if (currentView === 'all') {
                const factoryName = currentMode === 'kranburi' ? 'ครบุรี' : 'สีคิ้ว';
                subtitleText = `โรงงาน${factoryName}`;
            } else {
                const factoryName = currentZoneMode === 'kranburi' ? 'ครบุรี' : 'สีคิ้ว';
                subtitleText = `โรงงาน${factoryName} ประจำเขต ${selectedZone}`;
            }
            ctx.fillText(subtitleText, tempCanvas.width / 2, 70);
            
            // วาดวันที่
            ctx.fillStyle = '#6c757d';
            ctx.font = '16px Sarabun';
            
            const now = new Date();
            const day = now.getDate();
            const month = now.getMonth() + 1;
            const year = (now.getFullYear() + 543).toString().slice(-2);
            const dateText = `วันที่ ${day}/${month}/${year}`;
            ctx.fillText(dateText, tempCanvas.width / 2, 95);
            
            // วาดกราฟ
            ctx.drawImage(chartCanvas, 0, 120);
            
            // สร้างลิงก์ดาวน์โหลด
            const link = document.createElement('a');
            link.download = `รายงานอ้อยเข้าหีบ_${currentMode}_${currentView === 'all' ? 'ทั้งหมด' : 'เขต' + selectedZone}_${new Date().getTime()}.png`;
            link.href = tempCanvas.toDataURL('image/png');
            link.click();
            
            alert('บันทึกรายงานเป็นภาพเรียบร้อยแล้ว');
        }

        // ดาวน์โหลดรายงาน
        function downloadReport() {
            const now = new Date();
            const day = now.getDate();
            const month = now.getMonth() + 1;
            const year = now.getFullYear() + 543;
            
            let reportContent = `รายงานอ้อยเข้าหีบ ปี 2569\n`;
            reportContent += `วันที่สร้างรายงาน: ${day}/${month}/${year}\n`;
            reportContent += `โหมด: ${currentView === 'all' ? 'สะสมทั้งหมด' : 'รายเขต'}\n`;
            reportContent += `พื้นที่: ${currentView === 'all' ? getFileName(currentMode) : `เขต ${selectedZone}`}\n\n`;
            
            reportContent += `สรุปผล:\n`;
            reportContent += `- น้ำหนักอ้อยสุทธิรวม: ${document.getElementById('totalWeightDashboard').textContent} ตัน\n\n`;
            
            const blob = new Blob([reportContent], { type: 'text/plain' });
            const url = URL.createObjectURL(blob);
            const a = document.createElement('a');
            a.href = url;
            a.download = `รายงานอ้อยเข้าหีบ_${day}-${month}-${year}.txt`;
            document.body.appendChild(a);
            a.click();
            document.body.removeChild(a);
            URL.revokeObjectURL(url);
            
            alert('ดาวน์โหลดรายงานเรียบร้อยแล้ว');
        }

        // รีเซ็ตทั้งหมด
        function resetAll() {
            if (confirm('ต้องการล้างข้อมูลทั้งหมดหรือไม่? การดำเนินการนี้ไม่สามารถย้อนกลับได้')) {
                Object.keys(uploadedFiles).forEach(key => {
                    uploadedFiles[key] = null;
                });
                
                document.getElementById('file1').value = '';
                document.getElementById('file2').value = '';
                document.getElementById('file3').value = '';
                
                ['kranburi', 'sikhio', 'farmers'].forEach(fileType => {
                    const fileId = getFileId(fileType);
                    document.getElementById(`fileStatus${fileId}`).style.display = 'none';
                    document.getElementById(`uploadArea${fileId}`).className = 'upload-area';
                    updateFileStatus(fileType, 'pending', 'รออัพโหลดไฟล์');
                });
                
                document.getElementById('tableHeader').innerHTML = `
                    <th>ไฟล์</th>
                    <th>ตัวอย่างข้อมูล (5 แถวแรก)</th>
                `;
                document.getElementById('tableBody').innerHTML = `
                    <tr>
                        <td colspan="2" class="no-data">ยังไม่มีข้อมูล กรุณาอัพโหลดไฟล์</td>
                    </tr>
                `;
                
                document.getElementById('fileCount').textContent = '0/3';
                document.getElementById('totalRows').textContent = '0';
                document.getElementById('totalWeight').textContent = '0';
                document.getElementById('percentageTarget').textContent = '0%';
                
                document.getElementById('validationSummary').style.display = 'none';
                
                document.getElementById('validateBtn').disabled = true;
                document.getElementById('generateReportBtn').disabled = true;
                document.getElementById('downloadBtn').disabled = true;
                
                showMainPage();
                
                if (chartInstance) {
                    chartInstance.destroy();
                    chartInstance = null;
                }
            }
        }

        // รีเซ็ตไฟล์
        function resetFile(fileType) {
            const fileId = getFileId(fileType);
            document.getElementById(`file${fileId}`).value = '';
            document.getElementById(`fileStatus${fileId}`).style.display = 'none';
            updateUploadArea(fileType, 'default');
            updateFileStatus(fileType, 'pending', 'รออัพโหลดไฟล์');
            uploadedFiles[fileType] = null;
            updateSummaryCards();
        }

        // Helper Functions
        function getFileId(fileType) {
            const map = { kranburi: 1, sikhio: 2, farmers: 3 };
            return map[fileType] || 1;
        }

        function getFileName(fileType) {
            const map = {
                kranburi: 'อ้อยเข้าหีบ ครบุรี',
                sikhio: 'อ้อยเข้าหีบ สีคิ้ว',
                farmers: 'ฐานข้อมูลชาวไร่'
            };
            return map[fileType] || 'ไฟล์ข้อมูล';
        }

        function updateUploadArea(fileType, status) {
            const fileId = getFileId(fileType);
            const uploadArea = document.getElementById(`uploadArea${fileId}`);
            uploadArea.className = 'upload-area';
            
            if (status === 'active' || status === 'success') {
                uploadArea.classList.add('active');
            } else if (status === 'error') {
                uploadArea.classList.add('error');
            }
        }

        function updateFileStatus(fileType, status, message) {
            const fileId = getFileId(fileType);
            const statusText = document.getElementById(`statusText${fileId}`);
            const statusIcon = document.getElementById(`statusIcon${fileId}`);
            const statusDesc = document.getElementById(`statusDesc${getFileId(fileType)}`);
            
            statusText.textContent = message;
            statusText.className = `status-text ${status}`;
            
            let iconClass = '';
            let icon = '';
            
            switch(status) {
                case 'pending':
                    iconClass = 'pending';
                    icon = 'fa-clock';
                    break;
                case 'uploading':
                    iconClass = 'pending';
                    icon = 'fa-spinner fa-spin';
                    break;
                case 'success':
                    iconClass = 'success';
                    icon = 'fa-check-circle';
                    break;
                case 'error':
                    iconClass = 'error';
                    icon = 'fa-exclamation-circle';
                    break;
            }
            
            statusIcon.className = `status-icon ${iconClass}`;
            statusIcon.innerHTML = `<i class="fas ${icon}"></i>`;
            
            statusDesc.textContent = message;
        }

        function updateValidationStatus(fileType, validation) {
            const fileId = getFileId(fileType);
            const statusIcon = document.getElementById(`statusIcon${fileId}`);
            const statusDesc = document.getElementById(`statusDesc${fileId}`);
            
            if (validation.isValid) {
                statusIcon.className = 'status-icon success';
                statusIcon.innerHTML = '<i class="fas fa-check-circle"></i>';
                statusDesc.textContent = `ตรวจสอบแล้ว (${validation.totalRows} แถว)`;
            } else {
                statusIcon.className = 'status-icon error';
                statusIcon.innerHTML = '<i class="fas fa-exclamation-circle"></i>';
                statusDesc.textContent = validation.message;
            }
        }

        function formatFileSize(bytes) {
            if (bytes === 0) return '0 Bytes';
            const k = 1024;
            const sizes = ['Bytes', 'KB', 'MB', 'GB'];
            const i = Math.floor(Math.log(bytes) / Math.log(k));
            return parseFloat((bytes / Math.pow(k, i)).toFixed(2)) + ' ' + sizes[i];
        }

        function parseDateColumn(dateString) {
            if (!dateString) return null;
            
            const parts = dateString.split('/');
            if (parts.length === 3) {
                const day = parseInt(parts[0]);
                const month = parseInt(parts[1]);
                const year = parseInt(parts[2]);
                
                if (year === 1968 || year === 1969) {
                    return `${day}/${month.toString().padStart(2, '0')}`;
                }
            }
            return null;
        }

        function formatDateForChart(dateStr) {
            const [day, month] = dateStr.split('/');
            return `${day}/${month}`;
        }

        // Drag and drop functionality
        document.addEventListener('DOMContentLoaded', function() {
            const uploadAreas = document.querySelectorAll('.upload-area');
            
            uploadAreas.forEach(area => {
                area.addEventListener('dragover', function(e) {
                    e.preventDefault();
                    this.classList.add('active');
                });
                
                area.addEventListener('dragleave', function() {
                    this.classList.remove('active');
                });
                
                area.addEventListener('drop', function(e) {
                    e.preventDefault();
                    this.classList.remove('active');
                    
                    const files = e.dataTransfer.files;
                    if (files.length > 0) {
                        let fileType = '';
                        if (this.id === 'uploadArea1') fileType = 'kranburi';
                        else if (this.id === 'uploadArea2') fileType = 'sikhio';
                        else if (this.id === 'uploadArea3') fileType = 'farmers';
                        
                        if (fileType) {
                            const input = document.getElementById(`file${getFileId(fileType)}`);
                            const dataTransfer = new DataTransfer();
                            dataTransfer.items.add(files[0]);
                            input.files = dataTransfer.files;
                            
                            handleFileUpload(input, fileType);
                        }
                    }
                });
            });
        });
    </script>
</body>
</html>
```

สรุปการแก้ไขที่สำคัญ:

1. แกน Y แบบซ้าย-ขวา:

· แกน Y ซ้าย (primary): "ตันรายวัน"
  · แสดงข้อมูลน้ำหนักรายวันเป็นแท่งกราฟ
  · แสดงแท่งเป้าหมายเป็นพื้นหลัง
· แกน Y ขวา (secondary): "ตันสะสม"
  · แสดงข้อมูลน้ำหนักสะสมเป็นเส้นกราฟ
  · แบ่งช่วงละ 100,000 ตัน
  · สิ้นสุดที่ 2,500,000 ตัน
  · แสดงหน่วยเป็น K (พันตัน)

2. แท่งเป้าหมายพื้นหลัง:

· แท่งสีส้มจาง (rgba(255, 152, 0, 0.1))
· วางทับกันกับแท่งข้อมูลจริง (ไม่เหลื่อม)
· ช่วยให้เห็นว่าวันไหนมีอ้อยเข้าหีบตามเป้าหมาย

3. การตั้งค่าแกน Y ซ้าย:

· สะสมทั้งหมด - ครบุรี:
  · เป้าหมาย: 35,000 ตัน/วัน
  · แบ่งช่องละ 2,500 ตัน
  · ขีดเล็กทุก 1,250 ตัน
  · สิ้นสุดที่ 40,000 ตัน
· สะสมทั้งหมด - สีคิ้ว:
  · เป้าหมาย: 12,500 ตัน/วัน
  · แบ่งช่องละ 1,000 ตัน
  · ขีดเล็กทุก 500 ตัน
  · สิ้นสุดที่ 15,000 ตัน
· รายเขต: ตั้งค่าตามแต่ละเขตอย่างละเอียด

4. การตั้งค่าแกน Y ขวา:

· แบ่งช่วงละ 100,000 ตัน
· สิ้นสุดที่ 2,500,000 ตัน
· แสดงหน่วยเป็น K (เช่น 500K = 500,000 ตัน)

5. ลบเส้นกริดแนวตั้ง:

· ลบเส้นกริดแนวตั้งทั้งหมดออก
· ลดความเข้มของเส้นกริดแนวนอน (ความเข้ม 0.05)

6. Legend:

· แสดง 3 สี:
  1. สีแท่งน้ำหนักรายวัน (ฟ้า/เขียว)
  2. สีแท่งเป้าหมาย (ส้ม)
  3. สีเส้นตันสะสม (ม่วง)

7. Tooltip:

· แสดงข้อมูลทั้ง 3 dataset:
  · เป้าหมายรายวัน
  · น้ำหนักรายวัน
  · ตันสะสม

ระบบนี้สามารถคัดลอกโค้ดทั้งหมดไปวางใน Notepad บันทึกเป็นไฟล์ .html แล้วรันได้ทันที
