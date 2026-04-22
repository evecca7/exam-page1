<!DOCTYPE html>
<html lang="zh-CN">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<!-- 1. 修改了页面标题 -->
<title>易慧家科技 智能门窗销售考试</title>
<style>
*{margin:0;padding:0;box-sizing:border-box;font-family:Microsoft YaHei,Arial,sans-serif}
body{background:#f7f8fa;padding:20px}
.container{max-width:900px;margin:0 auto;background:#fff;border-radius:16px;padding:40px;box-shadow:0 4px 20px rgba(0,0,0,0.06)}
.logo{text-align:center;margin-bottom:20px}
.logo img{height:80px} /* 调整LOGO高度，适配你的图 */
.header{text-align:center;margin-bottom:30px}
.header h1{font-size:26px;color:#1f2937;margin-bottom:8px}
.header p{color:#6b7280;font-size:15px}
.login-box{background:#f9fafb;padding:20px;border-radius:12px;margin-bottom:30px;display:flex;justify-content:center;align-items:center;gap:12px}
.login-box label{font-size:16px;font-weight:500;color:#374151}
.login-box input{padding:12px 16px;border:1px solid #d1d5db;border-radius:8px;font-size:15px;width:220px;outline:0}
.login-box input:focus{border-color:#2563eb}
.section{margin-bottom:36px}
.section-title{font-size:18px;background:#eff6ff;padding:12px 18px;border-left:5px solid #2563eb;border-radius:8px;margin-bottom:20px;font-weight:600}
.question{margin-bottom:22px}
.question p{font-size:15px;color:#1f2937;margin-bottom:10px;line-height:1.5}
.answer{width:100%;height:80px;padding:14px 16px;border:1px solid #d1d5db;border-radius:10px;font-size:15px;resize:vertical;outline:0}
.answer:focus{border-color:#2563eb}
.submit-box{text-align:center;margin-top:40px}
#submitBtn{background:#2563eb;color:#fff;border:none;padding:14px 40px;border-radius:10px;font-size:16px;font-weight:500;cursor:pointer}
#submitBtn:hover{background:#1d4ed8}
</style>
</head>

<body>
<div class="container">
  <div class="logo">
    <!-- 2. 替换为你的LOGO（下面说明如何用自己的图） -->
    <img src="https://raw.githubusercontent.com/evecca7/exam-page/main/logo.png" alt="易慧家科技">
  </div>
  <div class="header">
    <h1>易慧家科技 智能门窗销售考试</h1>
    <p>请填写手机号与姓名，完成后提交自动生成答卷</p>
  </div>

  <div class="login-box">
    <label>手机号：</label>
    <input type="text" id="phone" placeholder="请输入手机号">
    <label>姓名：</label>
    <input type="text" id="username" placeholder="请输入姓名">
  </div>

  <div class="section">
    <div class="section-title">一、前装产品基础类</div>
    <div class="question"><p>1. 全景门配套材料有哪些？品牌、系列？</p><textarea class="answer" data-title="1"></textarea></div>
    <div class="question"><p>2. 重型门配套材料有哪些？品牌、系列？</p><textarea class="answer" data-title="2"></textarea></div>
    <div class="question"><p>3. 极简门配套材料有哪些？品牌、系列？</p><textarea class="answer" data-title="3"></textarea></div>
    <div class="question"><p>4. 完美系统材料有哪些？品牌、系列？</p><textarea class="answer" data-title="4"></textarea></div>
    <div class="question"><p>5. 平开窗适配材料有哪些？品牌、系列？</p><textarea class="answer" data-title="5"></textarea></div>
    <div class="question"><p>6. 隐藏式平开电机是有刷还是无刷？结构、算法、特点？</p><textarea class="answer" data-title="6"></textarea></div>
    <div class="question"><p>7. 隐藏式平开电机有几种？</p><textarea class="answer" data-title="7"></textarea></div>
    <div class="question"><p>8. 直驱推拉电机结构、算法、特点？</p><textarea class="answer" data-title="8"></textarea></div>
    <div class="question"><p>9. 直驱推拉电机有几款型号？</p><textarea class="answer" data-title="9"></textarea></div>
    <div class="question"><p>10. 智能锁有哪些？</p><textarea class="answer" data-title="10"></textarea></div>
    <div class="question"><p>11. 锁要不要接线？</p><textarea class="answer" data-title="11"></textarea></div>
    <div class="question"><p>12. 锁具跟其它指纹锁具有什么区别？</p><textarea class="answer" data-title="12"></textarea></div>
    <div class="question"><p>13. 直驱电机一共有几个尺寸？</p><textarea class="answer" data-title="13"></textarea></div>
    <div class="question"><p>14. 控制器有几款？</p><textarea class="answer" data-title="14"></textarea></div>
    <div class="question"><p>15. APP有哪几款？</p><textarea class="answer" data-title="15"></textarea></div>
  </div>

  <div class="section">
    <div class="section-title">二、后装产品基础类</div>
    <div class="question"><p>1. 后装产品都有哪些？</p><textarea class="answer" data-title="后1"></textarea></div>
    <div class="question"><p>2. 能装在哪些窗户上？</p><textarea class="answer" data-title="后2"></textarea></div>
    <div class="question"><p>3. 安装对窗户有什么要求？</p><textarea class="answer" data-title="后3"></textarea></div>
    <div class="question"><p>4. 有哪些功能？</p><textarea class="answer" data-title="后4"></textarea></div>
    <div class="question"><p>5. 跟其它同类产品有什么区别？</p><textarea class="answer" data-title="后5"></textarea></div>
  </div>

  <div class="section">
    <div class="section-title">三、客户常见问题类</div>
    <div class="question"><p>1. 你们公司干这个多久了？</p><textarea class="answer" data-title="客1"></textarea></div>
    <div class="question"><p>2. 你们公司在哪里？</p><textarea class="answer" data-title="客2"></textarea></div>
    <div class="question"><p>3. 产品可以做哪些门/窗类型？</p><textarea class="answer" data-title="客3"></textarea></div>
    <div class="question"><p>4. 我想开模怎么办？</p><textarea class="answer" data-title="客4"></textarea></div>
    <div class="question"><p>5. 我不想开模怎么办？</p><textarea class="answer" data-title="客5"></textarea></div>
    <div class="question"><p>6. 有哪些企业用你们产品？</p><textarea class="answer" data-title="客6"></textarea></div>
    <div class="question"><p>7. 电机质保多久？</p><textarea class="answer" data-title="客7"></textarea></div>
    <div class="question"><p>8. 锁具质保多久？</p><textarea class="answer" data-title="客8"></textarea></div>
    <div class="question"><p>9. 控制器质保多久？</p><textarea class="answer" data-title="客9"></textarea></div>
    <div class="question"><p>10. 皮带质保多久？</p><textarea class="answer" data-title="客10"></textarea></div>
    <div class="question"><p>11. 不符合质保范围怎么处理？</p><textarea class="answer" data-title="客11"></textarea></div>
    <div class="question"><p>12. 客户说价格太贵怎么回应？</p><textarea class="answer" data-title="客12"></textarea></div>
    <div class="question"><p>13. 售后是你们做还是我们做？</p><textarea class="answer" data-title="客13"></textarea></div>
    <div class="question"><p>14. 控制器只有一款吗？</p><textarea class="answer" data-title="客14"></textarea></div>
    <div class="question"><p>15. 可以连接哪些智能家居？</p><textarea class="answer" data-title="客15"></textarea></div>
    <div class="question"><p>16. 产品有哪些功能？</p><textarea class="answer" data-title="客16"></textarea></div>
  </div>

  <div class="submit-box">
    <button id="submitBtn">提交试卷</button>
  </div>
</div>

<script>
async function getIp() {
  try {
    let res = await fetch('https://api.ipify.org?format=json');
    let data = await res.json();
    return data.ip;
  } catch (e) { return '获取失败'; }
}

function getDevice() {
  const ua = navigator.userAgent;
  if (ua.match(/iPhone|iPad/)) return '苹果设备：' + ua;
  if (ua.match(/Android/)) return '安卓设备：' + ua;
  if (ua.match(/Windows/)) return 'Windows电脑：' + ua;
  if (ua.match(/Mac/)) return 'Mac电脑：' + ua;
  return '未知设备：' + ua;
}

document.getElementById('submitBtn').onclick = async function () {
  const phone = document.getElementById('phone').value.trim();
  const name = document.getElementById('username').value.trim();
  if (!phone) { alert('请填写手机号！'); return; }
  if (!name) { alert('请填写姓名！'); return; }

  const ip = await getIp();
  const device = getDevice();
  let content = '📄 易慧家科技销售考试答卷\n';
  content += '==============================\n';
  content += '👤 姓名：' + name + '\n';
  content += '📞 手机号：' + phone + '\n';
  content += '🌐 IP地址：' + ip + '\n';
  content += '📱 设备信息：' + device + '\n';
  content += '==============================\n\n';

  const questions = document.querySelectorAll('.question p');
  const answers = document.querySelectorAll('.answer');
  for (let i=0; i<questions.length; i++) {
    content += questions[i].innerText + '\n';
    content += '▶ 答案：' + (answers[i].value.trim() || '【未作答】') + '\n\n';
  }

  const blob = new Blob([content], { type: 'text/plain' });
  const url = URL.createObjectURL(blob);
  const a = document.createElement('a');
  a.href = url;
  a.download = name + '_' + phone + '_易慧家科技考试答卷.txt';
  a.click();

  alert('提交成功！请将下载的答卷文件发送给管理员');
};
</script>
</body>
</html>
