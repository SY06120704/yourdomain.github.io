<!DOCTYPE html>
<html lang="ja">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>出張撮影・動画撮影サービス利用規約 | MADE IN CREW</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Helvetica Neue', Arial, 'Hiragino Kaku Gothic ProN', 'Hiragino Sans', Meiryo, sans-serif;
            line-height: 1.7;
            color: #333;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            min-height: 100vh;
        }

        .container {
            max-width: 900px;
            margin: 0 auto;
            background: #fff;
            box-shadow: 0 20px 40px rgba(0,0,0,0.1);
            border-radius: 12px;
            overflow: hidden;
            margin-top: 2rem;
            margin-bottom: 2rem;
        }

        .header {
            background: linear-gradient(135deg, #2c3e50 0%, #34495e 100%);
            color: white;
            padding: 3rem 2rem;
            text-align: center;
            position: relative;
        }

        .header::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background: url('data:image/svg+xml,<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 100 100"><defs><pattern id="grain" width="100" height="100" patternUnits="userSpaceOnUse"><circle cx="20" cy="20" r="1" fill="white" opacity="0.1"/><circle cx="80" cy="40" r="1" fill="white" opacity="0.1"/><circle cx="40" cy="80" r="1" fill="white" opacity="0.1"/></pattern></defs><rect width="100" height="100" fill="url(%23grain)"/></svg>') repeat;
            opacity: 0.3;
        }

        .header h1 {
            font-size: 2rem;
            font-weight: 300;
            margin-bottom: 0.5rem;
            position: relative;
            z-index: 1;
        }

        .header .subtitle {
            font-size: 1.1rem;
            opacity: 0.9;
            position: relative;
            z-index: 1;
        }

        .brand {
            font-weight: 600;
            color: #64ffda;
        }

        .content {
            padding: 2rem;
        }

        .toc {
            background: #f8f9fa;
            border-radius: 8px;
            padding: 1.5rem;
            margin-bottom: 2rem;
            border-left: 4px solid #667eea;
        }

        .toc h2 {
            font-size: 1.2rem;
            margin-bottom: 1rem;
            color: #2c3e50;
        }

        .toc-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 0.5rem;
        }

        .toc a {
            color: #667eea;
            text-decoration: none;
            padding: 0.3rem 0;
            border-radius: 4px;
            transition: all 0.3s ease;
            font-size: 0.9rem;
        }

        .toc a:hover {
            color: #2c3e50;
            background: rgba(102, 126, 234, 0.1);
            padding-left: 0.5rem;
        }

        .section {
            margin-bottom: 3rem;
            scroll-margin-top: 2rem;
        }

        .section h2 {
            font-size: 1.5rem;
            color: #2c3e50;
            margin-bottom: 1.5rem;
            padding-bottom: 0.5rem;
            border-bottom: 2px solid #667eea;
            position: relative;
        }

        .section h2::before {
            content: attr(data-number);
            background: #667eea;
            color: white;
            padding: 0.2rem 0.6rem;
            border-radius: 20px;
            font-size: 0.8rem;
            margin-right: 0.8rem;
            font-weight: 600;
        }

        .subsection {
            margin-bottom: 1.5rem;
        }

        .subsection h3 {
            color: #34495e;
            font-size: 1.1rem;
            margin-bottom: 0.8rem;
            font-weight: 600;
        }

        .highlight-box {
            background: linear-gradient(135deg, #ff6b6b 0%, #ee5a24 100%);
            color: white;
            padding: 1.5rem;
            border-radius: 8px;
            margin: 1rem 0;
            box-shadow: 0 4px 15px rgba(255, 107, 107, 0.3);
        }

        .highlight-box h4 {
            margin-bottom: 0.8rem;
            font-size: 1.1rem;
        }

        .fee-table {
            background: #f8f9fa;
            border-radius: 8px;
            overflow: hidden;
            margin: 1rem 0;
            border: 1px solid #e9ecef;
        }

        .fee-table table {
            width: 100%;
            border-collapse: collapse;
        }

        .fee-table th {
            background: #667eea;
            color: white;
            padding: 1rem;
            text-align: left;
            font-weight: 600;
        }

        .fee-table td {
            padding: 0.8rem 1rem;
            border-bottom: 1px solid #e9ecef;
        }

        .fee-table tr:hover {
            background: rgba(102, 126, 234, 0.05);
        }

        .info-box {
            background: #e3f2fd;
            border-left: 4px solid #2196f3;
            padding: 1rem 1.5rem;
            margin: 1rem 0;
            border-radius: 0 8px 8px 0;
        }

        .warning-box {
            background: #fff3e0;
            border-left: 4px solid #ff9800;
            padding: 1rem 1.5rem;
            margin: 1rem 0;
            border-radius: 0 8px 8px 0;
        }

        .process-flow {
            display: flex;
            align-items: center;
            gap: 1rem;
            margin: 1rem 0;
            flex-wrap: wrap;
        }

        .process-step {
            background: #667eea;
            color: white;
            padding: 0.8rem 1.2rem;
            border-radius: 25px;
            font-size: 0.9rem;
            font-weight: 500;
            flex: 1;
            min-width: 150px;
            text-align: center;
            position: relative;
        }

        .process-step:not(:last-child)::after {
            content: '→';
            position: absolute;
            right: -1.5rem;
            color: #667eea;
            font-weight: bold;
        }

        ul li {
            margin-bottom: 0.5rem;
            padding-left: 0.5rem;
        }

        .footer {
            background: #2c3e50;
            color: white;
            text-align: center;
            padding: 2rem;
            margin-top: 3rem;
        }

        .back-to-top {
            position: fixed;
            bottom: 2rem;
            right: 2rem;
            background: #667eea;
            color: white;
            width: 50px;
            height: 50px;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            text-decoration: none;
            box-shadow: 0 4px 15px rgba(102, 126, 234, 0.3);
            transition: all 0.3s ease;
            opacity: 0;
            transform: translateY(100px);
        }

        .back-to-top.visible {
            opacity: 1;
            transform: translateY(0);
        }

        .back-to-top:hover {
            background: #5a67d8;
            transform: translateY(-3px);
        }

        @media (max-width: 768px) {
            .container {
                margin: 1rem;
                border-radius: 8px;
            }

            .header {
                padding: 2rem 1rem;
            }

            .header h1 {
                font-size: 1.5rem;
            }

            .content {
                padding: 1.5rem;
            }

            .toc-grid {
                grid-template-columns: 1fr;
            }

            .process-flow {
                flex-direction: column;
            }

            .process-step:not(:last-child)::after {
                content: '↓';
                position: static;
                margin: 0.5rem 0;
            }

            .fee-table {
                font-size: 0.9rem;
            }

            .back-to-top {
                bottom: 1rem;
                right: 1rem;
            }
        }

        @media print {
            body {
                background: white;
            }
            
            .container {
                box-shadow: none;
                margin: 0;
            }
            
            .back-to-top {
                display: none;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <header class="header">
            <h1>出張撮影・動画撮影サービス利用規約</h1>
            <p class="subtitle"><span class="brand">MADE IN CREW</span> サービス利用条件</p>
        </header>

        <div class="content">
            <div class="info-box">
                <p>この利用規約（以下「本規約」といいます。）は、<strong>MADE IN CREW</strong>（以下「当方」といいます。）が提供する出張撮影・動画撮影サービスの利用条件を定めるものです。クライアント様（以下「お客様」といいます。）には、本規約にご同意いただいた上で、当方サービスをご利用いただきます。</p>
            </div>

            <div class="toc">
                <h2>目次</h2>
                <div class="toc-grid">
                    <a href="#service">第1条　サービス内容</a>
                    <a href="#location">第2条　撮影場所・許可・準備事項</a>
                    <a href="#contract">第3条　契約の成立</a>
                    <a href="#payment">第4条　料金・支払い</a>
                    <a href="#cancellation">第5条　キャンセル・変更</a>
                    <a href="#shooting">第6条　撮影実施・トラブル対応</a>
                    <a href="#editing">第7条　編集・制作</a>
                    <a href="#delivery">第8条　納品・検収</a>
                    <a href="#reshoot">第9条　再撮影の条件</a>
                    <a href="#data">第10条　データ保管・管理</a>
                    <a href="#ip">第11条　知的財産権</a>
                    <a href="#privacy">第12条　個人情報・機密情報の取扱い</a>
                    <a href="#liability">第13条　責任の範囲</a>
                    <a href="#equipment">第14条　機材・備品の取扱い</a>
                    <a href="#breach">第15条　契約違反・解除</a>
                    <a href="#dispute">第16条　紛争解決</a>
                    <a href="#notice">第17条　通知方法</a>
                    <a href="#amendment">第18条　規約の変更</a>
                    <a href="#others">第19条　その他</a>
                </div>
            </div>

            <section id="service" class="section">
                <h2 data-number="第1条">サービス内容</h2>
                
                <div class="subsection">
                    <h3>1.1 サービスの範囲</h3>
                    <p>当方は、お客様のご要望に応じて以下のサービスを提供いたします：</p>
                    <ul>
                        <li>写真撮影サービス</li>
                        <li>動画撮影サービス</li>
                        <li>写真・動画の組み合わせサービス</li>
                    </ul>
                </div>

                <div class="subsection">
                    <h3>1.2 成果物の仕様</h3>
                    <p>具体的な撮影内容、時間、カット数または時間内撮影分全ての納品、動画の長さ・編集範囲、納品データ形式（写真：RAW、JPEG等／動画：MP4、MOV等）、解像度・フレームレート等は個別契約で定めるものとします。</p>
                </div>

                <div class="subsection">
                    <h3>1.3 サービスの実施</h3>
                    <p>当方は、お客様とのご契約に基づき、合意した場所・日時・内容にて制作業務を実施いたします。</p>
                </div>

                <div class="subsection">
                    <h3>1.4 機材・備品の提供</h3>
                    <p>当方は、制作に必要な機材・備品を適切に準備し、必要に応じてお客様に使用していただく場合があります。</p>
                </div>
            </section>

            <section id="location" class="section">
                <h2 data-number="第2条">撮影場所・許可・準備事項</h2>
                
                <div class="subsection">
                    <h3>2.1 撮影許可の責任</h3>
                    <p>撮影場所において必要な許可（施設利用許可、撮影許可、動画撮影許可等）の取得は、原則としてお客様の責任において行っていただきます。当方も事前打ち合わせにて必要な許可について確認・アドバイスを行い、許可取得をサポートいたします。当方が許可取得を代行する場合は、別途費用を申し受けます。</p>
                </div>

                <div class="subsection">
                    <h3>2.2 撮影環境の準備</h3>
                    <p>お客様は、撮影に適した環境（照明、空調、騒音対策等）を可能な限りご準備ください。当方も事前に撮影環境を確認し、必要に応じて改善提案をいたします。双方の協力により良好な撮影環境を整備できなかった場合の品質影響については、予めご了承ください。</p>
                </div>

                <div class="subsection">
                    <h3>2.3 撮影対象者の準備</h3>
                    <p>撮影対象者の体調管理、時間管理はお客様の責任となります。撮影対象者の遅刻・欠席・体調不良等により撮影時間が短縮された場合でも、基本料金に変更はありません。</p>
                </div>

                <div class="subsection">
                    <h3>2.4 動画撮影時の特別事項</h3>
                    <p>動画撮影の場合、以下の事項についてもご協力をお願いいたします：</p>
                    <ul>
                        <li>撮影中の静粛性の確保（音声収録のため）</li>
                        <li>電源設備の確保（長時間撮影のため）</li>
                        <li>撮影機材設置スペースの確保</li>
                    </ul>
                    <p>当方も事前に現場確認を行い、必要な環境整備についてアドバイスいたします。</p>
                </div>
            </section>

            <section id="contract" class="section">
                <h2 data-number="第3条">契約の成立</h2>
                
                <div class="subsection">
                    <h3>3.1 契約成立の時期</h3>
                    <p>契約は、お客様から正式なご発注の意思表示をいただき、当方がこれを受諾した時点で成立いたします。</p>
                </div>

                <div class="subsection">
                    <h3>3.2 見積書の有効期限</h3>
                    <p>当方が提示する見積書の有効期限は、特別な記載がない限り発行日より30日間とさせていただきます。</p>
                </div>
            </section>

            <section id="payment" class="section">
                <h2 data-number="第4条">料金・支払い</h2>
                
                <div class="subsection">
                    <h3>4.1 料金体系</h3>
                    <p>当方は、制作内容に応じた料金を見積書にて明示いたします。料金は、基本料金と追加オプション料金により構成されます。</p>
                </div>

                <div class="subsection">
                    <h3>4.2 支払い方法・期限</h3>
                    <p>お支払い方法・期限については、見積書に記載の内容に準じます。見積書に特別な記載がない場合は、銀行振込にて請求書発行日より30日以内にお支払いいただきます。</p>
                </div>

                <div class="subsection">
                    <h3>4.3 追加費用</h3>
                    <p>契約後にお客様のご要望により業務内容に変更が生じた場合、追加料金が発生することがあります。その際は、事前にお客様にご相談し、ご承認をいただいてから実施いたします。</p>
                </div>
            </section>

            <section id="cancellation" class="section">
                <h2 data-number="第5条">キャンセル・変更</h2>
                
                <div class="highlight-box">
                    <h4>重要：キャンセル料について</h4>
                    <p>お客様のご都合によりキャンセルされる場合のキャンセル料は以下の通りです</p>
                </div>

                <div class="fee-table">
                    <table>
                        <thead>
                            <tr>
                                <th>キャンセル時期</th>
                                <th>キャンセル料</th>
                            </tr>
                        </thead>
                        <tbody>
                            <tr>
                                <td>実施予定日の14日前～7日前</td>
                                <td>無料</td>
                            </tr>
                            <tr>
                                <td>実施予定日の6日前～3日前</td>
                                <td>契約金額の30%</td>
                            </tr>
                            <tr>
                                <td>実施予定日の2日前～1日前</td>
                                <td>契約金額の50%</td>
                            </tr>
                            <tr>
                                <td>実施予定日の当日</td>
                                <td>契約金額の100%</td>
                            </tr>
                        </tbody>
                    </table>
                </div>

                <div class="subsection">
                    <h3>5.2 日程変更</h3>
                    <p>日程変更をご希望の場合は、可能な限り対応いたします。ただし、以下の変更手数料を申し受けます。</p>
                    
                    <div class="fee-table">
                        <table>
                            <thead>
                                <tr>
                                    <th>変更時期</th>
                                    <th>変更手数料</th>
                                </tr>
                            </thead>
                            <tbody>
                                <tr>
                                    <td>実施予定日の7日前まで</td>
                                    <td>無料（1回まで）<br>2回目以降：契約金額の10%</td>
                                </tr>
                                <tr>
                                    <td>実施予定日の6日前～3日前</td>
                                    <td>契約金額の20%</td>
                                </tr>
                                <tr>
                                    <td>実施予定日の2日前～1日前</td>
                                    <td>契約金額の50%</td>
                                </tr>
                                <tr>
                                    <td>実施予定日の当日</td>
                                    <td>契約金額の100%</td>
                                </tr>
                            </tbody>
                        </table>
                    </div>
                    
                    <div class="info-box">
                        <p><strong>注意：</strong>当方都合による変更の場合は、上記費用は発生いたしません</p>
                    </div>
                </div>

                <div class="subsection">
                    <h3>5.3 天候等による日程変更</h3>
                    <p>天候不良その他不可抗力により撮影が困難と判断される場合は、双方協議の上、日程変更を行うことができます。この場合、変更手数料は発生いたしません。</p>
                </div>

                <div class="subsection">
                    <h3>5.4 当方都合による変更・中止</h3>
                    <p>当方の都合により契約を履行できない場合は、お客様にお支払いいただいた料金の全額を返金いたします。</p>
                </div>
            </section>

            <section id="shooting" class="section">
                <h2 data-number="第6条">撮影実施・トラブル対応</h2>
                
                <div class="subsection">
                    <h3>6.1 撮影時間の管理</h3>
                    <p>撮影時間は契約で定めた時間を基本とし、お客様都合による延長は30分単位で追加料金を申し受けます。ただし、当方の提案による撮影内容の追加や、双方の協議による延長については、柔軟に対応いたします。動画撮影の場合、セットアップ・撤収時間も含めて管理いたします。</p>
                </div>

                <div class="subsection">
                    <h3>6.2 機材トラブル時の対応</h3>
                    <p>当方の機材故障により撮影継続が困難となった場合、可能な限り代替機材での撮影継続に努めます。やむを得ず撮影が中断・中止となった場合は、進行状況に応じた日程変更または一部返金（最大で契約金額の50%を上限）にて誠実に対応いたします。お客様にはご迷惑をおかけしないよう、予備機材の準備にも努めております。</p>
                </div>

                <div class="subsection">
                    <h3>6.3 撮影中の事故・安全管理</h3>
                    <p>撮影現場での安全管理は双方で注意いたします。当方も安全確保に最大限配慮いたしますが、撮影対象者および関係者の怪我・事故については、当方の重大な過失を除き責任を負いません。</p>
                </div>

                <div class="subsection">
                    <h3>6.4 データ消失・破損時の対応</h3>
                    <p>撮影データの消失・破損が当方の責めに帰すべき事由で発生した場合、無償での再撮影または料金返金で対応いたします。データ保護には万全を期しておりますが、お客様の逸失利益等については責任を負いません。</p>
                </div>

                <div class="subsection">
                    <h3>6.5 動画撮影時の音声品質</h3>
                    <p>動画撮影における音声品質確保のため、当方も事前に音響環境の確認を行い、必要に応じて改善提案をいたします。双方の協力により改善できない現場環境に起因する音声不具合については、予めご了承ください。</p>
                </div>
            </section>

            <section id="editing" class="section">
                <h2 data-number="第7条">編集・制作</h2>
                
                <div class="subsection">
                    <h3>7.1 動画編集サービス</h3>
                    <p>動画撮影において編集作業が含まれる場合、編集内容（カット編集、テロップ挿入、BGM追加等）は個別契約で定めるものとします。</p>
                </div>

                <div class="subsection">
                    <h3>7.2 編集プロセスと確認</h3>
                    <p>編集作業は以下のプロセスで進行いたします：</p>
                    
                    <div class="process-flow">
                        <div class="process-step">初稿データの制作・提出</div>
                        <div class="process-step">お客様による内容確認・承認</div>
                        <div class="process-step">最終仕上げ・納品</div>
                    </div>
                    
                    <div class="warning-box">
                        <p><strong>重要：</strong>編集内容の確認には、初稿データ提出後にお客様による明示的な確認・承認をお願いしております。ご確認後の構成変更・内容追加は別途料金が発生します。</p>
                    </div>
                </div>

                <div class="subsection">
                    <h3>7.3 編集の修正対応</h3>
                    <p>編集完了後の修正については、以下の通りといたします：</p>
                    <ul>
                        <li>軽微な修正（誤字修正、色調微調整等）：無料修正回数内で対応</li>
                        <li>大幅な修正（構成変更、追加編集等）：別途料金で対応</li>
                    </ul>
                </div>

                <div class="subsection">
                    <h3>7.4 編集に必要な素材</h3>
                    <p>編集に必要な素材（BGM、効果音、ロゴデータ等）の提供はお客様の責任において行っていただきます。有料素材を使用する場合は、事前に協議の上、別途実費を申し受けます。</p>
                </div>
            </section>

            <section id="delivery" class="section">
                <h2 data-number="第8条">納品・検収</h2>
                
                <div class="subsection">
                    <h3>8.1 納品期限・形式</h3>
                    <div class="fee-table">
                        <table>
                            <thead>
                                <tr>
                                    <th>サービス種別</th>
                                    <th>納品期限</th>
                                </tr>
                            </thead>
                            <tbody>
                                <tr>
                                    <td>写真撮影</td>
                                    <td>撮影完了後、原則として7営業日以内</td>
                                </tr>
                                <tr>
                                    <td>動画撮影（編集なし）</td>
                                    <td>撮影完了後、原則として3営業日以内</td>
                                </tr>
                                <tr>
                                    <td>動画撮影（編集あり）</td>
                                    <td>編集内容により個別に納期を設定</td>
                                </tr>
                            </tbody>
                        </table>
                    </div>
                    <p>納品方法は、オンラインストレージまたはその他合意した方法によります。お客様のご要望に応じて、可能な限り早期納品にも対応いたします。</p>
                </div>

                <div class="subsection">
                    <h3>8.2 検収期間</h3>
                    <p>データ納品後、お客様による検収期間を7日間とします。期間内にご連絡がない場合は、承認されたものとみなします。検収期間の延長は、最大で納品日から14日以内を上限とします。</p>
                </div>

                <div class="subsection">
                    <h3>8.3 検収後の修正</h3>
                    <p>検収完了後は、当方の明らかな制作ミス（写真：ピンボケ、露出不良等／動画：音声不同期、画質不良等の技術的な問題）については無償で対応いたします。軽微な修正や追加要望については、お客様との協議の上、新規案件として対応いたします。</p>
                </div>

                <div class="subsection">
                    <h3>8.4 大量データ納品時の取扱い</h3>
                    <p>時間内撮影分全てを納品する場合、データの選別・編集はお客様の責任において行っていただきます。また、大量データとなる場合は、納品方法について事前に協議し、お客様にとって最適な方法を選択いたします。</p>
                </div>
            </section>

            <section id="reshoot" class="section">
                <h2 data-number="第9条">再撮影の条件</h2>
                
                <div class="subsection">
                    <h3>9.1 当方都合による再撮影</h3>
                    <p>当方の明らかな技術的ミス（設定ミス、撮影指示の誤解等）による再撮影は、無償で対応いたします。</p>
                </div>

                <div class="subsection">
                    <h3>9.2 お客様都合による再撮影</h3>
                    <p>お客様の追加要望による再撮影は、新規案件として別途お見積もりいたします。</p>
                </div>

                <div class="subsection">
                    <h3>9.3 動画撮影の再収録</h3>
                    <p>動画撮影における再収録の場合、編集作業が発生している場合は編集費用についても別途協議いたします。</p>
                </div>
            </section>

            <section id="data" class="section">
                <h2 data-number="第10条">データ保管・管理</h2>
                
                <div class="subsection">
                    <h3>10.1 データ保管期間</h3>
                    <div class="fee-table">
                        <table>
                            <thead>
                                <tr>
                                    <th>データ種別</th>
                                    <th>保管期間</th>
                                </tr>
                            </thead>
                            <tbody>
                                <tr>
                                    <td>写真データ</td>
                                    <td>納品後3ヶ月間保管</td>
                                </tr>
                                <tr>
                                    <td>動画データ（素材）</td>
                                    <td>納品後3ヶ月間保管</td>
                                </tr>
                                <tr>
                                    <td>編集プロジェクトファイル</td>
                                    <td>納品後1ヶ月間保管</td>
                                </tr>
                            </tbody>
                        </table>
                    </div>
                    <p>それ以降の保管は保証いたしません。長期保管をご希望の場合は、別途保管料を申し受けます。</p>
                </div>

                <div class="subsection">
                    <h3>10.2 データの取扱い</h3>
                    <p>納品後にお客様がデータを編集・加工した場合、それに起因する不具合や品質劣化については責任を負いません。</p>
                </div>

                <div class="subsection">
                    <h3>10.3 編集ファイルの取扱い</h3>
                    <p>動画編集において使用したプロジェクトファイルは、原則として納品対象に含まれません。プロジェクトファイルの納品をご希望の場合は、事前にご相談ください。</p>
                </div>
            </section>

            <section id="ip" class="section">
                <h2 data-number="第11条">知的財産権</h2>
                
                <div class="subsection">
                    <h3>11.1 成果物の著作権</h3>
                    <p>制作した成果物の著作権は、料金完済後にお客様に譲渡いたします。ただし、当方の制作実績として使用する権利を留保させていただきます。</p>
                </div>

                <div class="subsection">
                    <h3>11.2 第三者の権利・BGM等の取扱い</h3>
                    <p>動画編集において使用するBGM、効果音、画像素材等について、当方も第三者の著作権侵害が生じないよう注意いたします。ただし、なお、当方が提供するBGM・素材については、商用利用可能な範囲での使用確認を行っておりますが、最終的な使用媒体における検出・制限等の影響については責任を負いかねます。</p>
                    
                    <div class="warning-box">
                        <p><strong>YouTube・SNS利用時のご注意：</strong>商用利用可能なBGM・効果音の使用に努めておりますが、YouTube、SNS等の自動検出システムによる広告制限や削除・制限等については保証いたしかねます。</p>
                    </div>
                </div>

                <div class="subsection">
                    <h3>11.3 ポートフォリオ・制作実績としての使用</h3>
                    <p>当方は、お客様の事前承諾を得て、制作した成果物を当方のポートフォリオや制作実績として紹介・掲載することができるものとします。なお、承諾は電子メール・書面など記録可能な手段により確認を行います。</p>
                </div>

                <div class="subsection">
                    <h3>11.4 ポートフォリオ掲載の範囲</h3>
                    <p>ポートフォリオ掲載について承諾をいただいた場合の使用範囲は、以下の通りとします。</p>
                    <ul>
                        <li>当方ウェブサイト、SNS、営業資料等での掲載</li>
                        <li>制作実績の紹介・プレゼンテーション資料での使用</li>
                        <li>業界関連の展示会・イベント等での展示</li>
                    </ul>
                    <p>なお、お客様名の表示については、別途ご相談の上決定いたします。</p>
                </div>
            </section>

            <section id="privacy" class="section">
                <h2 data-number="第12条">個人情報・機密情報の取扱い</h2>
                
                <div class="subsection">
                    <h3>12.1 個人情報の保護</h3>
                    <p>当方は、業務上知り得たお客様の個人情報を適切に管理し、法令に基づく場合を除き第三者に開示いたしません。</p>
                </div>

                <div class="subsection">
                    <h3>12.2 機密保持</h3>
                    <p>当方は、業務上知り得たお客様の機密情報を厳重に管理し、業務目的以外に使用いたしません。</p>
                </div>
            </section>

            <section id="liability" class="section">
                <h2 data-number="第13条">責任の範囲</h2>
                
                <div class="subsection">
                    <h3>13.1 免責事項</h3>
                    <p>以下の事由により生じた損害について、当方は責任を負いません。ただし、事前の確認・協議により回避可能な事項については、当方も最大限協力いたします。</p>
                    <ul>
                        <li>天災地変、公共交通機関の運休・遅延など不可抗力による場合</li>
                        <li>お客様の指示・要望に起因する場合</li>
                        <li>第三者による妨害行為による場合</li>
                        <li>事前確認を行ったにも関わらず撮影許可の取得ができなかった場合</li>
                        <li>撮影対象者の遅刻・欠席・体調不良による撮影時間短縮（可能な範囲で調整対応いたします）</li>
                        <li>双方の協力により改善を図ったが解決できない現場の音響環境による音声品質の低下</li>
                        <li>事前確認を行ったにも関わらず生じた第三者の著作権を侵害する素材使用によるトラブル</li>
                    </ul>
                </div>

                <div class="subsection">
                    <h3>13.2 損害賠償の制限</h3>
                    <p>当方の責任は、契約金額を上限とし、間接損害・逸失利益については責任を負いません。ただし、当方の過失に基づく損害についても、当該契約に基づいて実際に受領した金額を超えて責任を負うものではありません。</p>
                </div>
            </section>

            <section id="equipment" class="section">
                <h2 data-number="第14条">機材・備品の取扱い</h2>
                
                <div class="subsection">
                    <h3>14.1 貸出機材の管理責任</h3>
                    <p>当方がお客様に貸与した機材・備品について、お客様は善良な管理者の注意をもって取り扱うものとします。</p>
                </div>

                <div class="subsection">
                    <h3>14.2 紛失・破損時の責任</h3>
                    <p>お客様の故意・重過失により機材・備品が紛失・破損した場合、修理費用または相当額をご負担いただきます。</p>
                </div>
            </section>

            <section id="breach" class="section">
                <h2 data-number="第15条">契約違反・解除</h2>
                
                <div class="subsection">
                    <h3>15.1 契約違反</h3>
                    <p>お客様が本規約に違反した場合、当方は契約を解除し、損害賠償を請求することができます。</p>
                </div>

                <div class="subsection">
                    <h3>15.2 合意解除</h3>
                    <p>双方の合意により、いつでも契約を解除することができます。</p>
                </div>
            </section>

            <section id="dispute" class="section">
                <h2 data-number="第16条">紛争解決</h2>
                
                <div class="subsection">
                    <h3>16.1 協議による解決</h3>
                    <p>本規約に関する紛争が生じた場合は、まず当事者間で誠実に協議し、解決に努めます。</p>
                </div>

                <div class="subsection">
                    <h3>16.2 管轄裁判所</h3>
                    <p>協議により解決しない場合は、当方所在地を管轄する地方裁判所を第一審の専属管轄裁判所とします。</p>
                </div>
            </section>

            <section id="notice" class="section">
                <h2 data-number="第17条">通知方法</h2>
                <p>当方とお客様間の通知は、書面、電子メール、またはその他合意した方法により行います。</p>
            </section>

            <section id="amendment" class="section">
                <h2 data-number="第18条">規約の変更</h2>
                <p>当方は、必要に応じて本規約を変更することがあります。変更する場合は、事前にお客様にご通知いたします。なお、規約の変更は、原則として新たなご契約時に適用されるものであり、既存の契約には影響いたしません。</p>
            </section>

            <section id="others" class="section">
                <h2 data-number="第19条">その他</h2>
                
                <div class="subsection">
                    <h3>19.1 準拠法</h3>
                    <p>本規約は日本法に準拠します。</p>
                </div>

                <div class="subsection">
                    <h3>19.2 分離可能性</h3>
                    <p>本規約の一部が無効となった場合でも、他の条項の有効性には影響しません。</p>
                </div>
            </section>
        </div>

        <footer class="footer">
            <p><strong>制定日：2025年6月16日</strong></p>
            <p>&copy; 2025 MADE IN CREW. All Rights Reserved.</p>
        </footer>
    </div>

    <a href="#" class="back-to-top" id="backToTop">↑</a>

    <script>
        // スムーススクロール
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                const target = document.querySelector(this.getAttribute('href'));
                if (target) {
                    target.scrollIntoView({
                        behavior: 'smooth',
                        block: 'start'
                    });
                }
            });
        });

        // トップに戻るボタン
        const backToTop = document.getElementById('backToTop');
        
        window.addEventListener('scroll', () => {
            if (window.pageYOffset > 300) {
                backToTop.classList.add('visible');
            } else {
                backToTop.classList.remove('visible');
            }
        });

        backToTop.addEventListener('click', (e) => {
            e.preventDefault();
            window.scrollTo({
                top: 0,
                behavior: 'smooth'
            });
        });

        // 目次のハイライト機能
        const sections = document.querySelectorAll('.section');
        const tocLinks = document.querySelectorAll('.toc a');

        function highlightCurrentSection() {
            let current = '';
            sections.forEach(section => {
                const sectionTop = section.offsetTop;
                const sectionHeight = section.clientHeight;
                if (window.pageYOffset >= sectionTop - 100) {
                    current = section.getAttribute('id');
                }
            });

            tocLinks.forEach(link => {
                link.style.fontWeight = 'normal';
                link.style.color = '#667eea';
                if (link.getAttribute('href') === '#' + current) {
                    link.style.fontWeight = 'bold';
                    link.style.color = '#2c3e50';
                }
            });
        }

        window.addEventListener('scroll', highlightCurrentSection);

        // 印刷時の最適化
        window.addEventListener('beforeprint', () => {
            document.body.style.background = 'white';
        });

        window.addEventListener('afterprint', () => {
            document.body.style.background = 'linear-gradient(135deg, #667eea 0%, #764ba2 100%)';
        });
    </script>
</body>
</html>
