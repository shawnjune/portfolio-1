<!DOCTYPE html>
<html lang="zh">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>朱尚旺的作品集</title>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/gsap/3.12.5/gsap.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/gsap/3.12.5/ScrollTrigger.min.js"></script>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'PingFang SC', 'Microsoft YaHei', sans-serif;
        }

        :root {
            --primary-color: #a78bfa;
            --text-color: #e5e7eb;
            --bg-color: #111827;
            --section-spacing: 5rem;
        }

        body {
            line-height: 1.6;
            color: var(--text-color);
            background-color: var(--bg-color);
        }

        .navbar {
            position: fixed;
            top: 1rem;
            left: 50%;
            transform: translateX(-50%);
            width: auto;
            background: rgba(31, 41, 55, 0.95) !important;
            backdrop-filter: blur(8px);
            padding: 0.75rem 1.5rem;
            border-radius: 9999px;
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.2);
            z-index: 1000;
        }

        .nav-links {
            display: flex;
            gap: 2rem;
        }

        .nav-links a {
            color: #9ca3af;
            padding: 0.5rem 1.5rem;
            border-radius: 50px;
            transition: all 0.5s cubic-bezier(0.4, 0, 0.2, 1);
            text-decoration: none;
            position: relative;
            overflow: hidden;
        }

        .nav-links a::after {
            content: '';
            position: absolute;
            bottom: 0;
            left: 50%;
            width: 0;
            height: 2px;
            background: #a78bfa;
            transition: all 0.5s cubic-bezier(0.4, 0, 0.2, 1);
            transform: translateX(-50%);
        }

        .nav-links a:hover::after,
        .nav-links a.active::after {
            width: 90%;
        }

        .nav-links a:hover,
        .nav-links a.active {
            color: #a78bfa;
            background: rgba(167, 139, 250, 0.1);
            transform: translateY(-2px);
            padding: 0.5rem 2rem;
            border-radius: 50px;
        }

        .hero {
            height: 100vh;
            display: flex;
            align-items: center;
            justify-content: center;
            text-align: center;
            background: linear-gradient(135deg, #4f46e5, #7c3aed);
            color: white;
            padding: 2rem;
        }

        .hero-content {
            max-width: 800px;
        }

        .hero-content img {
            width: 200px;
            height: 200px;
            border-radius: 50%;
            margin-bottom: 2rem;
            border: 4px solid white;
            object-fit: cover;
            transform-origin: 30% 30%;
            transition: transform 0.6s cubic-bezier(0.34, 1.56, 0.64, 1);
        }

        .hero-content img:hover {
            transform: scale(1.15) translate(10px, -10px);
        }

        .hero h1 {
            font-size: 3rem;
            margin-bottom: 1rem;
        }

        .hero p {
            font-size: 1.2rem;
            margin-bottom: 2rem;
        }

        .section {
            padding: var(--section-spacing) 2rem;
            max-width: 1200px;
            margin: 0 auto;
        }

        .section-title {
            text-align: center;
            margin-bottom: 3rem;
            font-size: 2rem;
            color: var(--primary-color);
        }

        /* 还原作品集网格为垂直布局 */
        .projects-grid {
            display: flex;
            flex-direction: column;
            gap: 3rem;
        }

        /* 还原项目卡片样��������� */
        .project-card {
            display: flex;
            flex-direction: row;
            align-items: center;
            gap: 2rem;
            padding: 2rem;
            background: rgba(31, 41, 55, 0.5);
            border: 1px solid rgba(75, 85, 99, 0.3);
            border-radius: 1rem;
            transition: all 0.5s cubic-bezier(0.4, 0, 0.2, 1);
            cursor: pointer;
        }

        /* 还原项目卡片中的图片尺寸 */
        .project-card img {
            width: 400px;
            height: 300px;
            object-fit: cover;
            border-radius: 0.5rem;
            order: 2;
            transition: transform 0.5s cubic-bezier(0.4, 0, 0.2, 1);
        }

        .project-card:hover {
            background: rgba(31, 41, 55, 0.8);
            border-color: rgba(167, 139, 250, 0.5);
            box-shadow: 0 0 20px rgba(167, 139, 250, 0.1);
        }

        .project-card:hover img {
            transform: rotate(-5deg) scale(1.02);
        }

        .project-content {
            flex: 1;
            padding: 0;
        }

        .project-content h3 {
            margin-bottom: 1rem;
            color: var(--primary-color);
        }

        .tags {
            display: flex;
            flex-wrap: wrap;
            gap: 0.5rem;
            margin-top: 1rem;
        }

        .tag {
            background: rgba(75, 85, 99, 0.5);
            color: #e5e7eb;
            padding: 0.5rem 1.2rem;
            border-radius: 20px;
            font-size: 1.1rem;
            transition: all 0.3s ease;
            cursor: pointer;
            margin: 0.5rem;
            position: relative;
        }

        .tag:hover {
            background: #7c3aed;
            color: white;
            transform: scale(1.05);
        }

        .contact-form {
            max-width: 600px;
            margin: 0 auto;
            background: rgba(31, 41, 55, 0.5);
            padding: 2rem;
            border-radius: 10px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            border: 1px solid rgba(75, 85, 99, 0.3);
        }

        .form-group {
            margin-bottom: 1.5rem;
        }

        .form-group label {
            display: block;
            margin-bottom: 0.5rem;
            font-weight: 500;
        }

        .form-group input,
        .form-group textarea {
            width: 100%;
            padding: 0.8rem;
            border: 1px solid rgba(75, 85, 99, 0.3);
            border-radius: 5px;
            font-size: 1rem;
            background: rgba(17, 24, 39, 0.8);
            color: #e5e7eb;
        }

        .btn {
            background: var(--primary-color);
            color: white;
            padding: 0.8rem 2rem;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            font-size: 1rem;
            transition: background 0.3s;
        }

        .btn:hover {
            background: #4f46e5;
        }

        footer {
            text-align: center;
            padding: 2rem;
            background: rgba(31, 41, 55, 0.5);
            color: #9ca3af;
            margin-top: var(--section-spacing);
        }

        @media (max-width: 768px) {
            .hero h1 {
                font-size: 2rem;
            }
            
            .nav-links {
                gap: 1rem;
            }

            .projects-grid {
                padding: 1rem;
                gap: 1rem;
            }

            .project-card {
                min-width: 300px;
                padding: 1rem;
            }

            .project-card img {
                width: 140px;
                height: 140px;
            }
        }

        .fade-up {
            opacity: 0;
            transform: translateY(20px);
            transition: all 0.6s ease;
        }

        .fade-up.visible {
            opacity: 1;
            transform: translateY(0);
        }

        .timeline {
            position: relative;
        }

        .timeline::before {
            content: '';
            position: absolute;
            left: 50%;
            top: 0;
            bottom: 0;
            width: 2px;
            background: rgba(75, 85, 99, 0.5);
            transform: translateX(-50%);
        }

        .timeline-item {
            display: flex;
            justify-content: space-between;
            margin-bottom: 3rem;
        }

        .timeline-item:nth-child(even) {
            flex-direction: row-reverse;
        }

        .timeline-content {
            width: 45%;
            padding: 1.5rem;
            background: rgba(31, 41, 55, 0.5);
            border-radius: 0.5rem;
            position: relative;
            border: 1px solid rgba(75, 85, 99, 0.3);
            transition: all 0.3s ease;
            cursor: pointer;
        }

        .timeline-dot {
            position: absolute;
            left: 50%;
            width: 1rem;
            height: 1rem;
            background: var(--primary-color);
            border-radius: 50%;
            transform: translateX(-50%);
        }

        @media (max-width: 968px) {
            .project-card {
                flex-direction: column-reverse;
                padding: 1.5rem;
            }

            .project-card img {
                width: 100%;
                height: 250px;
            }
        }

        .contact-info {
            display: flex;
            flex-direction: row;
            justify-content: center;
            gap: 2rem;
            margin-top: 2rem;
            flex-wrap: wrap;
        }

        .contact-item {
            flex: 0 1 auto;
            min-width: 280px;
            display: flex;
            align-items: center;
            gap: 1rem;
            padding: 1rem 2rem;
            background: rgba(31, 41, 55, 0.5);
            border: 1px solid rgba(75, 85, 99, 0.3);
            border-radius: 9999px;
            transition: all 0.3s ease;
        }

        .contact-item:hover {
            background: rgba(31, 41, 55, 0.8);
            border-color: rgba(167, 139, 250, 0.5);
            transform: translateY(-2px);
        }

        .contact-icon {
            color: var(--primary-color);
            display: flex;
            align-items: center;
            justify-content: center;
        }

        .contact-item span {
            font-size: 1.1rem;
        }

        @media (max-width: 768px) {
            .contact-item {
                width: 90%;
                justify-content: center;
            }
        }

        .modal {
            display: none;
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: rgba(0, 0, 0, 0);
            z-index: 2000;
            overflow: hidden;
            transition: background 0.8s cubic-bezier(0.4, 0, 0.2, 1);
        }

        .modal.active {
            display: block;
            background: rgba(0, 0, 0, 0.85);
        }

        /* 修改模态框内容区域的样式 */
        .modal-content {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100vh;
            margin: 0;
            padding: 0;
            display: flex;
            align-items: center;
            justify-content: center;  /* 添加水平居中 */
            transform: scale(0);
            opacity: 0;
            transition: all 0.8s cubic-bezier(0.34, 1.56, 0.64, 1);
        }

        .modal.active .modal-content {
            transform: scale(1);
            opacity: 1;
        }

        .modal-close {
            position: fixed;
            top: 2rem;
            right: 2rem;
            background: none;
            border: 2px solid white;
            border-radius: 50%;
            color: white;
            font-size: 2rem;
            cursor: pointer;
            width: 40px;
            height: 40px;
            display: flex;
            align-items: center;
            justify-content: center;
            transition: all 0.3s ease;
            z-index: 2001;
            padding: 0;
            line-height: 0;
            text-align: center;
        }

        .modal-close:hover {
            transform: rotate(90deg);
            background: rgba(255, 255, 255, 0.1);
        }

        /* 修改图片展示区域的样式 */
        .modal-gallery {
            display: flex !important;
            flex-direction: row !important;
            gap: 2rem;
            padding: 100 10000px;
            width: calc(100% - 240px);  /* 关键修改：考虑左右padding */
            height: 100%;
            overflow-x: auto;
            scroll-behavior: smooth;
            -ms-overflow-style: none;
            scrollbar-width: none;
            align-items: center;
            position: relative;  /* 修改定位方式 */
            margin: 0 auto;  /* 居中显示 */
        }

        /* 调整图片和视频缩略图大小 */
        .modal-gallery img,
        .video-thumbnail-container {
            height: 65vh;
            width: auto;
            flex-shrink: 0;
            border-radius: 0.5rem;
            transition: transform 0.3s ease;
        }

        /* 视频缩略图容器特定样式 */
        .video-thumbnail-container {
            position: relative;
            aspect-ratio: 16/9;
            background: rgba(31, 41, 55, 0.5);
            cursor: pointer;
        }

        .video-thumbnail-container img {
            height: 100%;
            width: 100%;
            object-fit: contain;
        }

        /* 隐藏滚动条 */
        .modal-gallery::-webkit-scrollbar {
            display: none;
        }

        /* 调整滚动区域的宽度和位置 */
        .scroll-area {
            position: fixed;
            top: 0;
            height: 100vh;
            width: 120px;
            z-index: 2001;
            display: flex;
            align-items: center;
            justify-content: center;
            opacity: 0.3;
            transition: opacity 0.3s ease;
            cursor: pointer;
        }

        .scroll-area.left {
            left: 0;
            background: linear-gradient(to right, rgba(229, 231, 235, 0.2), transparent);
        }

        .scroll-area.right {
            right: 0;
            background: linear-gradient(to left, rgba(229, 231, 235, 0.2), transparent);
        }

        .modal-content:hover .scroll-area {
            opacity: 0.3;
        }

        .scroll-area:hover {
            opacity: 0.7 !important;
        }

        .scroll-arrow {
            color: rgba(255, 255, 255, 0.9);
            font-size: 2.5rem;
            transition: all 0.3s ease;
            user-select: none;
            pointer-events: none;
        }

        .preview-modal {
            display: none;
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: rgba(0, 0, 0, 0);
            z-index: 3000;
            justify-content: center;
            align-items: center;
            transition: background 0.3s ease;
        }

        .preview-content {
            transform: scale(0);
            opacity: 0;
            transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1);
        }

        .preview-content img {
            max-height: 90vh;
            max-width: 90vw;
            object-fit: contain;
        }

        .preview-close {
            position: fixed;
            top: 2rem;
            right: 2rem;
            background: none;
            border: 2px solid white;
            border-radius: 50%;
            color: white;
            font-size: 2rem;
            cursor: pointer;
            width: 40px;
            height: 40px;
            display: flex;
            align-items: center;
            justify-content: center;
            transition: all 0.3s ease;
            z-index: 2001;
            padding: 0;
            line-height: 0;
            text-align: center;
        }

        .preview-close:hover {
            transform: rotate(90deg);
            background: rgba(255, 255, 255, 0.1);
        }

        /* 添加滑滚动果 */
        html {
            scroll-behavior: smooth;
        }

        /* 改进项目卡片悬停效果 */
        .project-card {
            cursor: pointer;
            transform: translateY(0);
            transition: all 0.4s cubic-bezier(0.4, 0, 0.2, 1);
        }

        .project-card:hover {
            transform: translateY(-10px);
        }

        /* 添加图片果 */
        .project-card img {
            transition: all 0.4s ease;
            filter: brightness(0.9);
        }

        .project-card:hover img {
            filter: brightness(1);
            transform: scale(1.05);
        }

        /* 改进移动端导航 */
        @media (max-width: 768px) {
            .navbar {
                width: 90%;
                padding: 0.5rem;
            }

            .nav-links {
                gap: 0.5rem;
            }

            .nav-links a {
                padding: 0.3rem 0.6rem;
                font-size: 0.9rem;
            }
        }

        /* 添加片预览模态框样式 */
        .preview-modal {
            display: none;
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: rgba(0, 0, 0, 0);
            z-index: 3000;
            justify-content: center;
            align-items: center;
            transition: background 0.3s ease;
        }

        .preview-content {
            transform: scale(0);
            opacity: 0;
            transition: all 0.8s cubic-bezier(0.34, 1.56, 0.64, 1);
        }

        .preview-content img {
            max-height: 90vh;
            max-width: 90vw;
            object-fit: contain;
        }

        .preview-close {
            position: absolute;
            top: -40px;
            right: 0;
            color: white;
            background: none;
            border: none;
            font-size: 2rem;
            cursor: pointer;
            padding: 0.5rem;
            transition: all 0.3s ease;
        }

        .preview-close:hover {
            transform: scale(1.1);
        }

        .scroll-progress-container {
            position: fixed;
            bottom: 40px;
            left: 50%;
            transform: translateX(-50%);
            width: 60%;
            height: 8px;
            background: rgba(255, 255, 255, 0.1);
            border-radius: 4px;
            cursor: pointer;
            transition: background 0.3s ease;
        }

        .scroll-progress-container:hover {
            background: rgba(255, 255, 255, 0.15);
        }

        .scroll-progress-bar {
            position: relative;
            height: 100%;
            width: 0;
            background: rgba(255, 255, 255, 0.4);
            border-radius: 4px;
            transition: all 0.1s ease;
        }

        .scroll-progress-container:hover .scroll-progress-bar {
            background: rgba(255, 255, 255, 0.6);
        }

        .scroll-handle {
            position: absolute;
            right: -6px;
            top: 50%;
            width: 12px;
            height: 12px;
            background: white;
            border-radius: 50%;
            transform: translate(0, -50%);
            opacity: 0;
            transition: opacity 0.3s ease;
        }

        .scroll-progress-container:hover .scroll-handle {
            opacity: 1;
        }

        /* 添加指针样式 */
        .scroll-progress-container {
            cursor: pointer;
        }

        .scroll-progress-container:hover {
            cursor: grab;
        }

        .scroll-progress-container:active {
            cursor: grabbing;
        }

        /* 调整进度条容器与图片的距离 */
        .modal-content {
            padding-bottom: 80px;
        }

        .modal-gallery {
            margin-bottom: 20px;
        }

        /* 防止选中图片和文本 */
        .modal-gallery {
            user-select: none;
            -webkit-user-select: none;
            -moz-user-select: none;
            -ms-user-select: none;
        }

        .modal-gallery img {
            pointer-events: auto !important;
            cursor: pointer;
        }

        .preview-modal.active {
            background: rgba(0, 0, 0, 0.95);
        }

        .preview-modal.active .preview-content {
            transform: scale(1);
            opacity: 1;
        }

        /* 添加经历部分的样式 */
        .timeline-content {
            width: 45%;
            padding: 1.5rem;
            background: rgba(31, 41, 55, 0.5);
            border-radius: 0.5rem;
            position: relative;
            border: 1px solid rgba(75, 85, 99, 0.3);
            transition: all 0.3s ease;
            cursor: pointer;
        }

        /* 添加紫色边框效果 */
        .timeline-content::before {
            content: '';
            position: absolute;
            left: 0;
            top: 0;
            width: 4px;
            height: 100%;
            background: linear-gradient(135deg, #4f46e5, #7c3aed);
            border-radius: 4px 0 0 4px;
            opacity: 0;
            transition: opacity 0.3s ease;
        }

        /* 悬浮效果 */
        .timeline-content:hover {
            transform: translateX(10px);
            background: rgba(31, 41, 55, 0.8);
            box-shadow: 0 4px 20px rgba(124, 58, 237, 0.1);
        }

        .timeline-content:hover::before {
            opacity: 1;
        }

        /* 为偶数项添加向效果 */
        .timeline-item:nth-child(even) .timeline-content:hover {
            transform: translateX(-10px);
        }

        .timeline-item:nth-child(even) .timeline-content::before {
            left: auto;
            right: 0;
            border-radius: 0 4px 4px 0;
        }

        /* 强文字反馈 */
        .timeline-content:hover h3,
        .timeline-content:hover h4 {
            color: #a78bfa;
        }

        .timeline-content:hover .text-purple-400 {
            color: #7c3aed;
        }

        /* 修改经历部分的悬浮果样式 */
        .timeline-content:hover h3,
        .timeline-content:hover h4 {
            color: inherit;  /* 移除悬浮时的颜色变化 */
        }

        /* 只保留年份的颜色变化 */
        .timeline-content .text-purple-400 {
            transition: color 0.3s ease;
        }

        .timeline-content:hover .text-purple-400 {
            color: #7c3aed;  /* 只有年份会变成深紫色 */
        }

        /* 保持其他悬浮效果不变 */
        .timeline-content:hover {
            transform: translateX(10px);
            background: rgba(31, 41, 55, 0.8);
            box-shadow: 0 4px 20px rgba(124, 58, 237, 0.1);
        }

        .timeline-item:nth-child(even) .timeline-content:hover {
            transform: translateX(-10px);
        }

        /* 添加下载简历按样式 */
        .download-resume {
            display: inline-block;
            margin-top: 2rem;
            padding: 1rem 2rem;
            background: rgba(255, 255, 255, 0.2);
            color: white;
            border: 2px solid white;
            border-radius: 30px;
            font-size: 1.1rem;
            text-decoration: none;
            transition: all 0.3s ease;
            backdrop-filter: blur(5px);
        }

        .download-resume:hover {
            background: white;
            color: #7c3aed;
            transform: translateY(-2px);
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.2);
        }

        /* 添烟花样式 */
        .firework {
            position: absolute;
            pointer-events: none;
            z-index: 9999;
        }

        .firework-particle {
            position: absolute;
            width: 5px;
            height: 5px;
            border-radius: 50%;
            animation: explode 0.8s cubic-bezier(0.45, 0.05, 0.55, 0.95) forwards;  /* 缩短总时长 */
            transform: translate(0, 0) scale(0);
            will-change: transform, opacity;
        }

        @keyframes explode {
            0% {
                transform: translate(0, 0) scale(0);
                opacity: 0;
            }
            8% {  /* 更快的初始放大 */
                transform: translate(0, 0) scale(1.2);
                opacity: 1;
            }
            20% {  /* 更的过渡 */
                transform: translate(calc(var(--tx) * 0.3), calc(var(--ty) * 0.3)) scale(1);
                opacity: 0.9;
            }
            100% {
                transform: translate(var(--tx), var(--ty)) scale(0);
                opacity: 0;
            }
        }

        .tag-tooltip {
            position: absolute;
            bottom: 100%;
            left: 50%;
            transform: translateX(-50%);
            padding: 0.5rem 1rem;
            background: rgba(31, 41, 55, 0.95);
            color: white;
            border-radius: 0.5rem;
            font-size: 0.9rem;
            white-space: nowrap;
            pointer-events: none;
            opacity: 0;
            transition: all 0.3s ease;
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.2);
            border: 1px solid rgba(167, 139, 250, 0.3);
            z-index: 1000;
            margin-bottom: 10px;
        }

        .tag-tooltip::after {
            content: '';
            position: absolute;
            top: 100%;
            left: 50%;
            transform: translateX(-50%);
            border-width: 5px;
            border-style: solid;
            border-color: rgba(31, 41, 55, 0.95) transparent transparent transparent;
        }

        .tag:hover .tag-tooltip {
            opacity: 1;
        }

        .scroll-trigger {
            position: absolute;
            top: 0;
            width: 100%;
            height: 100%;
            pointer-events: auto;
        }

        .modal-gallery img {
            position: relative;
            z-index: 10;
            pointer-events: auto !important;
        }

        /* 确保图片点击区域不与滚动区域重叠 */
        .modal-gallery {
            padding: 0 60px; /* 为滚动区域留出空间 */
        }

        .modal-gallery img {
            z-index: 2000;
            pointer-events: auto !important;
            cursor: pointer;
        }

        /* 移动端适配 */
        @media (max-width: 768px) {
            /* 导航栏适配 */
            .navbar {
                width: 100%;  /* 改为全宽 */
                padding: 0.5rem 1rem;
                display: flex;
                justify-content: center;
                background: rgba(31, 41, 55, 0.95) !important;
            }

            .nav-links {
                width: auto;  /* 改为自适应宽度 */
                display: flex;
                justify-content: center;
                flex-wrap: wrap;
                gap: 0.3rem;
                padding: 0;
                margin: 0 auto;  /* 添加水平居中 */
            }

            .nav-links a {
                padding: 0.3rem 0.6rem;
                font-size: 0.85rem;
                white-space: nowrap;  /* 防止文字换行 */
            }

            /* 主页内容适配 */
            .hero h1 {
                font-size: 2rem;
            }

            .hero p {
                font-size: 1rem;
            }

            .hero-content img {
                width: 150px;
                height: 150px;
            }

            /* 作品卡适配 */
            .project-card {
                flex-direction: column;
                padding: 1rem;
            }

            .project-card img {
                width: 100%;
                height: 200px;
                order: -1;  /* 图片显示在上方 */
            }

            .project-content {
                padding: 1rem 0;
            }

            /* 联系方式适配 */
            .contact-info {
                display: flex;
                flex-direction: column;
                align-items: center;
                gap: 1rem;
            }

            .contact-item {
                width: 90%;
                max-width: 320px;
                padding: 0.8rem 1.5rem;
                display: flex;
                align-items: center;
                justify-content: flex-start;  /* 左对齐内容 */
            }

            .contact-icon {
                width: 24px;  /* 固定图标宽度 */
                display: flex;
                justify-content: center;
                margin-right: 1rem;  /* 增加图标和文字的间距 */
            }

            .contact-item span {
                font-size: 0.95rem;
                white-space: nowrap;  /* 防止文字换行 */
            }

            /* 历时间线适配 */
            .timeline::before {
                left: 20px;  /* 时间线靠左 */
            }

            .timeline-item {
                flex-direction: column;
                padding-left: 40px;
            }

            .timeline-content {
                width: 100%;
            }

            .timeline-dot {
                left: 20px;
            }

            .timeline-item:nth-child(even) {
                flex-direction: column;
            }

            /* 技标签适配 */
            .tag {
                font-size: 0.85rem;
                padding: 0.3rem 0.8rem;
                margin: 0.25rem;
                white-space: nowrap;  /* 防止标签文字换行 */
            }

            /* 模态框适配 */
            .modal-gallery {
                padding: 0 60px;  /* 减小滚动区域宽度 */
            }

            .scroll-area {
                width: 60px;
            }

            .modal-gallery img,
            .modal-gallery video {
                height: 40vh;  /* 减小图片高度 */
            }

            .scroll-progress-container {
                width: 80%;  /* 增加进度条宽度 */
                bottom: 20px;
            }

            /* 关于我部分适配 */
            .text-lg {
                font-size: 1rem;
                padding: 0 1rem;
            }

            /* 下载简历按钮适配 */
            .download-resume {
                padding: 0.8rem 1.5rem;
                font-size: 1rem;
            }
        }

        /* 小屏幕适配 */
        @media (max-width: 480px) {
            .nav-links a {
                padding: 0.2rem 0.4rem;
                font-size: 0.8rem;
            }

            .hero-content img {
                width: 120px;
                height: 120px;
            }

            .section {
                padding: 3rem 1rem;
            }
        }

        .video-thumbnail-container {
            position: relative;
            display: inline-block;
            cursor: pointer;
            transition: transform 0.3s ease;
        }

        .video-thumbnail-container:hover {
            transform: scale(1.02);
        }

        .video-thumbnail-container img {
            width: auto;
            height: 60vh;
            object-fit: cover;
            border-radius: 0.5rem;
        }

        .play-button {
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            width: 64px;
            height: 64px;
            background: rgba(0, 0, 0, 0.6);
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            transition: all 0.3s ease;
        }

        .play-button svg {
            width: 48px;
            height: 48px;
            fill: white;
        }

        .video-thumbnail-container:hover .play-button {
            background: rgba(124, 58, 237, 0.8);
            transform: translate(-50%, -50%) scale(1.1);
        }

        /* 添加载动画 */
        @keyframes loading {
            0% { transform: rotate(0deg); }
            100% { transform: rotate(360deg); }
        }

        .loading-indicator {
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            width: 40px;
            height: 40px;
            border: 4px solid rgba(255, 255, 255, 0.3);
            border-radius: 50%;
            border-top-color: white;
            animation: loading 1s infinite linear;
            display: none;
        }

        .video-thumbnail-container.loading .loading-indicator {
            display: block;
        }

        .video-thumbnail-container video {
            width: auto;
            height: 60vh;
            border-radius: 0.5rem;
            background: rgba(0, 0, 0, 0.2);  /* 添加背景色，使加载时更美观 */
            object-fit: contain;
        }

        /* 美化视频控制器 */
        .video-thumbnail-container video::-webkit-media-controls-panel {
            background: rgba(0, 0, 0, 0.6);
        }

        .video-thumbnail-container video::-webkit-media-controls-play-button {
            border-radius: 50%;
            background: rgba(124, 58, 237, 0.8);
        }

        /* 移动端适配 */
        @media (max-width: 768px) {
            .video-thumbnail-container video {
                height: 40vh;  /* 移动端稍微降低高度 */
            }
        }

        /* 添加新的视频播放层式 */
        .video-overlay {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: rgba(0, 0, 0, 0.9);
            display: flex;
            justify-content: center;
            align-items: center;
            z-index: 3000;
            animation: fadeIn 0.3s ease;
        }

        .video-wrapper {
            position: relative;
            width: 90%;
            max-width: 1200px;
            aspect-ratio: 16/9;
        }

        .video-wrapper video {
            width: 100%;
            height: 100%;
            object-fit: contain;
            border-radius: 0.5rem;
            background: rgba(0, 0, 0, 0.2);
        }

        .video-close-btn {
            position: absolute;
            top: -40px;
            right: -40px;
            width: 40px;
            height: 40px;
            border: 2px solid white;
            border-radius: 50%;
            background: none;
            color: white;
            font-size: 24px;
            cursor: pointer;
            display: flex;
            align-items: center;
            justify-content: center;
            transition: all 0.3s ease;
        }

        .video-close-btn:hover {
            transform: rotate(90deg);
            background: rgba(255, 255, 255, 0.1);
        }

        @keyframes fadeIn {
            from {
                opacity: 0;
            }
            to {
                opacity: 1;
            }
        }

        /* ��整缩略图网格布局 */
        .modal-gallery {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
            gap: 2rem;
            padding: 2rem;
            width: 100%;
            max-width: 1400px;
            margin: 0 auto;
        }

        .video-thumbnail-container {
            width: 100%;
            aspect-ratio: 16/9;
        }

        .video-thumbnail-container img {
            width: 100%;
            height: 100%;
            object-fit: cover;
        }

        /* 移动端适配 */
        @media (max-width: 768px) {
            .video-wrapper {
                width: 95%;
            }
            
            .video-close-btn {
                top: -50px;
                right: 0;
            }
            
            .modal-gallery {
                grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
                gap: 1rem;
                padding: 1rem;
            }
        }

        /* 添加视频标题样式 */
        .video-title {
            position: absolute;
            bottom: -40px;
            left: 0;
            width: 100%;
            text-align: center;
            color: white;
            font-size: 1.2rem;
            padding: 10px;
        }

        /* 修改视频缩略图容器样式 */
        .video-thumbnail-container {
            height: 65vh;  /* 增加高度 */
            width: auto;   /* 自动宽度以保持比例 */
            aspect-ratio: 16/9;
            flex-shrink: 0;
            position: relative;
            border-radius: 0.5rem;
            background: rgba(31, 41, 55, 0.5);
            cursor: pointer;
            margin: 0 1rem;  /* 调整缩略图间距 */
        }

        .video-thumbnail-container img {
            height: 100%;
            width: 100%;
            object-fit: contain;  /* 保持原始比例 */
            border-radius: 0.5rem;
        }

        /* 调整网格布局 */
        .modal-gallery {
            display: grid;
            grid-template-columns: repeat(2, 1fr);  /* 改为两列布局 */
            gap: 2rem;
            padding: 2rem;
            width: 100%;
            max-width: 1400px;
            margin: 0 auto;
        }

        /* 移动端适配 */
        @media (max-width: 768px) {
            .modal-gallery {
                grid-template-columns: 1fr;  /* 移动端改为单列 */
                gap: 1rem;
                padding: 1rem;
            }
        }

        /* 确保模态框画廊使用水平flex布局 */
        .modal-gallery {
            display: flex !important;
            flex-direction: row !important;
            gap: 2rem;
            padding: -210 1020px;  /* 增加内边距以延伸到箭头区域 */
            width: 100%;
            height: 100%;
            overflow-x: auto;
            scroll-behavior: smooth;
            -ms-overflow-style: none;
            scrollbar-width: none;
            align-items: center;
        }

        /* 调整播放按钮大小 */
        .play-button {
            width: 80px;   /* 增大播放按钮 */
            height: 80px;
        }

        .play-button svg {
            width: 60px;   /* 增大播放图标 */
            height: 60px;
        }

        /* 移动端适配 */
        @media (max-width: 768px) {
            .video-thumbnail-container {
                height: 45vh;
            }
            
            .play-button {
                width: 60px;
                height: 60px;
            }
            
            .play-button svg {
                width: 40px;
                height: 40px;
            }
        }
    </style>
</head>
<body>
    <nav class="navbar">
        <div class="nav-links">
            <a href="#home">主页</a>
            <a href="#about">关于我</a>
            <a href="#experience">经历</a>
            <a href="#skills">技能</a>
            <a href="#projects">作品集</a>
            <a href="#contact">联系</a>
        </div>
    </nav>

    <section id="home" class="hero">
        <div class="hero-content">
            <img src="头像.png" alt="朱尚旺">
            <h1>朱尚旺</h1>
            <p>AI艺术创作者 / 设计师</p>
            <p>专注于AI辅助艺术创作，擅长数字艺术与传统设计的融合</p>
            <a href="./简历.jpg" class="download-resume" target="_blank">
                下载简历
            </a>
        </div>
    </section>

    <section id="about" class="section fade-up">
        <h2 class="section-title">关于我</h2>
        <p class="text-lg max-w-3xl mx-auto text-center leading-relaxed">
            我的艺术创作历程肇始于对人工智能的浓厚兴趣。在浙江师范大学攻读艺术设计硕士学位期间，
            我全身心投入到人工智能艺术创作领域的深入探究中，娴熟掌握了多种先进的工具与技术。
            我秉持将传统艺术与现代技术深度融合的理念，致力于创作出独具特色且富有创新性的艺术作品，
            为艺术领域的发展贡献力量。
        </p>
    </section>

    <section id="experience" class="section fade-up">
        <h2 class="section-title">经历</h2>
        <div class="timeline">
            <div class="timeline-item fade-up">
                <div class="timeline-content">
                    <span class="text-purple-400">2022 - 至今</span>
                    <h3 class="text-xl font-bold">浙江师范大学</h3>
                    <h4 class="text-purple-400 mb-2">艺术设计硕士</h4>
                    <p>在此期间，本人专注于人工智能艺术创作方向的研究。积极参与多个 AI 艺术创作项目，深入探索不同 AI 工具的融合应用，致力于人工智能艺术领域的发展贡献自己的力量，在实践与研究中不断提升专业素养。</p>
                </div>
                <div class="timeline-dot"></div>
            </div>

            <div class="timeline-item fade-up">
                <div class="timeline-content">
                    <span class="text-purple-400">2021 - 2022</span>
                    <h3 class="text-xl font-bold">独立艺术工作室</h3>
                    <h4 class="text-purple-400 mb-2">独立艺术家</h4>
                    <p>期间我专注于绘画学习，通过多种方式提升绘画与审美能力，并利用工作室资源探索 AI 辅助艺术创作。我临摹多种风格作品以提升绘画水平，通过多种途径提高审美，积极探索艺术创作新方向。</p>
                </div>
                <div class="timeline-dot"></div>
            </div>

            <div class="timeline-item fade-up">
                <div class="timeline-content">
                    <span class="text-purple-400">2017 - 2022</span>
                    <h3 class="text-xl font-bold">本科学习</h3>
                    <h4 class="text-purple-400 mb-2">视觉传达设计专业</h4>
                    <p>在本科学习阶段，系统且全面地研习了设计理论与实践相关内容，对于艺术创作的完整流程以及相关软件的运用有着深入的了解和熟练的掌握，从而为后续的 AI 艺术创作奠定了坚实的基础。</p>
                </div>
                <div class="timeline-dot"></div>
            </div>
        </div>
    </section>

    <section id="skills" class="section fade-up">
        <h2 class="section-title">技能</h2>
        <div style="text-align: center;">
            <span class="tag">
                PS
                <span class="tag-tooltip">Adobe Photoshop - 专业的图像处理和设计软件</span>
            </span>
            <span class="tag">
                AI
                <span class="tag-tooltip">Adobe Illustrator - 专业的矢量图形设计软件</span>
            </span>
            <span class="tag">
                TD
                <span class="tag-tooltip">TouchDesigner - 实时视觉程和交互设计平台</span>
            </span>
            <span class="tag">
                AE
                <span class="tag-tooltip">Adobe After Effects - 专业的视觉特效和动态图形软件</span>
            </span>
            <span class="tag">
                PR
                <span class="tag-tooltip">Adobe Premiere - 专业的视频剪辑和编辑软件</span>
            </span>
            <span class="tag">
                MAYA
                <span class="tag-tooltip">Autodesk Maya - 专业的3D建模和动画制作软件</span>
            </span>
            <span class="tag">
                UE
                <span class="tag-tooltip">Unreal Engine - 强大的实时3D创作平台</span>
            </span>
            <span class="tag">
                SD
                <span class="tag-tooltip">Stable Diffusion - 开源的AI图像生成模型</span>
            </span>
            <span class="tag">
                MJ
                <span class="tag-tooltip">Midjourney - 先进的AI艺术创作工具</span>
            </span>
            <span class="tag">
                Python
                <span class="tag-tooltip">通用编程语言，用于AI开发和自动化</span>
            </span>
            <span class="tag">
                GPT-SoVITS
                <span class="tag-tooltip">开源的AI语音克隆和合成工具</span>
            </span>
        </div>
    </section>

    <section id="projects" class="section">
        <h2 class="section-title">作品集</h2>
        <div class="projects-grid">
            <div class="project-card">
                <div class="project-content">
                    <h3>海报设计作品</h3>
                    <p>结合传统设计理念与现代审美，创作了一系列具有视觉冲击力的海报作品。涵盖商业广告、展览、社会议题等多个主题。</p>
                    <div class="tags">
                        <span class="tag">展览海报</span>
                        <span class="tag">商业海报</span>
                        <span class="tag">Photoshop</span>
                        <span class="tag">Illustrator</span>
                    </div>
                </div>
                <img src="作品封面/1.png" alt="海报设计作品">
            </div>

            <div class="project-card">
                <div class="project-content">
                    <h3>手绘艺术作品</h3>
                    <p>传统手绘与数字绘画相结合，展现独特的艺术风格。包括人物肖像、风景写生、概念设计等多种材料。</p>
                    <div class="tags">
                        <span class="tag">数字绘画</span>
                        <span class="tag">插画设计</span>
                        <span class="tag">黑白装饰画</span>
                        <span class="tag">彩色手绘</span>
                    </div>
                </div>
                <img src="作品封面/2.png" alt="手绘艺术作品">
            </div>

            <div class="project-card">
                <div class="project-content">
                    <h3>AI静态艺术作品</h3>
                    <p>用Stable Diffusion、Midjourney等AI工具，探索人工智能与艺术创作的边界，创作具有独特美学风格的静态作品。</p>
                    <div class="tags">
                        <span class="tag">Stable Diffusion</span>
                        <span class="tag">Midjourney</span>
                        <span class="tag">DALL-E</span>
                        <span class="tag">AI艺术</span>
                    </div>
                </div>
                <img src="作品封面/3.png" alt="AI静态艺术">
            </div>

            <div class="project-card">
                <div class="project-content">
                    <h3>AI动态艺术作品</h3>
                    <p>结合AI与动态设计，创作富有生命力的动态艺术作品。包括动态海报、视觉效果、AI影像等多种形式。</p>
                    <div class="tags">
                        <span class="tag">Animatediff</span>
                        <span class="tag">动态设计</span>
                        <span class="tag">Runway</span>
                        <span class="tag">视觉效果</span>
                    </div>
                </div>
                <img src="作品封面/4.png" alt="AI动态艺术">
            </div>

            <div class="project-card">
                <div class="project-content">
                    <h3>交互艺术装置</h3>
                    <p>结合AI技术与互动设计，打造沉浸式的艺术体验。通过声音、动作、触摸等多种方式与观众产生互动。</p>
                    <div class="tags">
                        <span class="tag">互动设计</span>
                        <span class="tag">TouchDesigner</span>
                        <span class="tag">AI生成</span>
                        <span class="tag">手势交互</span>
                    </div>
                </div>
                <img src="作品封面/5.png" alt="互动艺术作品">
            </div>
        </div>
    </section>

    <section id="contact" class="section fade-up">
        <h2 class="section-title">联系方式</h2>
        <div class="contact-info">
            <div class="contact-item">
                <i class="contact-icon">
                    <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                        <path d="M12 4c4.4 0 8 3.6 8 8s-3.6 8-8 8-8-3.6-8-8 3.6-8 8-8z"/>
                        <path d="M15 16l3 3"/>
                    </svg>
                </i>
                <span>357527685</span>
            </div>
            <div class="contact-item">
                <i class="contact-icon">
                    <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                        <path d="M22 16.92v3a2 2 0 0 1-2.18 2 19.79 19.79 0 0 1-8.63-3.07 19.5 19.5 0 0 1-6-6 19.79 19.79 0 0 1-3.07-8.67A2 2 0 0 1 4.11 2h3a2 2 0 0 1 2 1.72 12.84 12.84 0 0 0 .7 2.81 2 2 0 0 1-.45 2.11L8.09 9.91a16 16 0 0 0 6 6l1.27-1.27a2 2 0 0 1 2.11-.45 12.84 12.84 0 0 0 2.81.7A2 2 0 0 1 22 16.92z"/>
                    </svg>
                </i>
                <span>15270606566</span>
            </div>
            <div class="contact-item">
                <i class="contact-icon">
                    <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                        <path d="M4 4h16c1.1 0 2 .9 2 2v12c0 1.1-.9 2-2 2H4c-1.1 0-2-.9-2-2V6c0-1.1.9-2 2-2z"/>
                        <polyline points="22,6 12,13 2,6"/>
                    </svg>
                </i>
                <span>zsw357527685@163.com</span>
            </div>
        </div>
    </section>

    <footer>
        <p>© 2024 朱尚旺. 保留所有权利。</p>
    </footer>

    <div class="modal" id="projectModal">
        <button class="modal-close" onclick="closeModal()">×</button>
        <div class="modal-content">
            <div class="scroll-area left">
                <div class="scroll-arrow">&lt;</div>
            </div>
            <div class="scroll-area right">
                <div class="scroll-arrow">&gt;</div>
            </div>
            <div class="modal-gallery" id="modalGallery">
                <!-- 内容将通过 JavaScript 动态添加 -->
            </div>
            <div class="scroll-progress-container">
                <div class="scroll-progress-bar">
                    <div class="scroll-handle"></div>
                </div>
            </div>
        </div>
    </div>

    <div class="preview-modal" id="previewModal">
        <div class="preview-content">
            <button class="preview-close" onclick="closePreview()">×</button>
            <img id="previewImage" src="" alt="预览图片">
        </div>
    </div>

    <script>
        const navLinks = document.querySelectorAll('.nav-links a');
        const sections = document.querySelectorAll('section');

        function setActiveNav() {
            let current = '';
            sections.forEach(section => {
                const sectionTop = section.offsetTop;
                if (window.scrollY >= sectionTop - 100) {
                    current = section.getAttribute('id');
                }
            });

            navLinks.forEach(link => {
                if (link.getAttribute('href').slice(1) === current) {
                    if (!link.classList.contains('active')) {
                        // 加过渡动画
                        link.style.transition = 'all 0.5s cubic-bezier(0.4, 0, 0.2, 1)';
                        link.classList.add('active');
                    }
                } else {
                    link.classList.remove('active');
                }
            });
        }

        const fadeElements = document.querySelectorAll('.fade-up');
        
        const observer = new IntersectionObserver((entries) => {
            entries.forEach(entry => {
                if (entry.isIntersecting) {
                    entry.target.classList.add('visible');
                }
            });
        }, {
            threshold: 0.1
        });

        fadeElements.forEach(element => {
            observer.observe(element);
        });

        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                document.querySelector(this.getAttribute('href')).scrollIntoView({
                    behavior: 'smooth'
                });
            });
        });

        window.addEventListener('scroll', setActiveNav);

        const modal = document.getElementById('projectModal');
        const modalGallery = document.getElementById('modalGallery');

        const projectsData = {
            'poster': {
                title: '海报设计作品',
                description: '创作了一系列具有视觉冲击力的海报作品。涵盖商业广告、文化活动、社会议题等多个主题。',
                folder: './海报作品',
                images: [1, 2, 3, 4, 5],
                type: 'image'
            },
            'drawing': {
                title: '手绘艺术作品',
                description: '传统手绘与数字绘画相结合，展现独特的艺术风格。',
                folder: './手绘作品',
                images: [1, 2, 3, 4, 5],
                type: 'image'
            },
            'ai-static': {
                title: 'AI静态艺术品',
                description: '运用Stable Diffusion、Midjourney等AI工具，探索人工智能与艺术创作的边界。',
                folder: './AI静态艺术作品',
                images: [1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11],
                type: 'image'
            },
            'ai-dynamic': {
                title: 'AI动态艺术作品',
                description: '结合AI动态设计，创作富有生命力的动态艺术作品。',
                folder: './AI动态艺术作品',  // 根目录下的文件夹
                images: [1, 2, 3, 4, 5, 6],  // 更新为6个作品
                type: 'video',
                format: {
                    video: 'mp4',
                    thumbnail: {  // 为每个视频指定对应的缩略图格式
                        3: 'jpg',  // 第3个视频使用jpg格式���缩略图
                        default: 'png'  // 其他视频使用png格式的缩略图
                    }
                }
            },
            'interactive': {
                title: '交互艺术装置',
                description: '融合AI技术与互动设计，打造沉浸式的艺术体验。',
                folder: './交互艺术装置',  // 指向根目录下的交互艺术装置文件夹
                images: [
                    'AI评价风格转绘',
                    'AI驱动实时绘画',
                    'TD-AI实时绘画',
                    'TD-生成3d模型',
                    '大语言模型文字冒险游戏'
                ],
                type: 'video',
                format: {
                    video: 'mp4',
                    thumbnail: 'png'
                }
            }
        };

        document.querySelectorAll('.project-card').forEach((card, index) => {
            const projectIds = ['poster', 'drawing', 'ai-static', 'ai-dynamic', 'interactive'];
            card.setAttribute('data-project-id', projectIds[index]);
            
            card.addEventListener('click', () => {
                const projectId = card.getAttribute('data-project-id');
                openModal(projectId);
            });
        });

        function openModal(projectId) {
            const project = projectsData[projectId];
            if (!project) return;
            
            // 获取点��的项目卡片中的图片位置
            const card = document.querySelector(`[data-project-id="${projectId}"]`);
            const cardImage = card.querySelector('img');
            const rect = cardImage.getBoundingClientRect();
            const modalContent = modal.querySelector('.modal-content');

            // 设置动画起始点为图片的中心
            modalContent.style.transformOrigin = `${rect.left + rect.width/2}px ${rect.top + rect.height/2}px`;
            
            // 显示模态框
            modal.style.display = 'block';
            
            // 备内容
            modalGallery.innerHTML = '';
            project.images.forEach((file, index) => {
                const number = index + 1;
                
                if (project.type === 'video') {
                    const thumbnailContainer = document.createElement('div');
                    thumbnailContainer.className = 'video-thumbnail-container';
                    
                    // 添加缩略图
                    const thumbnailImg = document.createElement('img');
                    // 对于交互艺术装置，使用完整文件名
                    if (typeof file === 'string') {
                        thumbnailImg.src = `${project.folder}/${file}.${project.format.thumbnail}`;
                        thumbnailImg.alt = `${project.title} 预览图`;
                    } else {
                        // 对于AI动态艺术作品，使用数字编号
                        const thumbnailFormat = project.format.thumbnail[number] || project.format.thumbnail.default;
                        thumbnailImg.src = `${project.folder}/${number}.${thumbnailFormat}`;
                        thumbnailImg.alt = `${project.title} 预览图 ${number}`;
                    }
                    
                    // 添加播放按钮
                    const playButton = document.createElement('div');
                    playButton.className = 'play-button';
                    playButton.innerHTML = `
                        <svg viewBox="0 0 24 24" width="48" height="48">
                            <path fill="white" d="M8 5v14l11-7z"/>
                        </svg>
                    `;
                    
                    thumbnailContainer.appendChild(thumbnailImg);
                    thumbnailContainer.appendChild(playButton);
                    
                    // 点击事件处理
                    thumbnailContainer.addEventListener('click', () => {
                        const videoOverlay = document.createElement('div');
                        videoOverlay.className = 'video-overlay';
                        
                        const videoWrapper = document.createElement('div');
                        videoWrapper.className = 'video-wrapper';
                        
                        const videoElement = document.createElement('video');
                        // 根据文件名类型选择正确的路径
                        videoElement.src = typeof file === 'string' 
                            ? `${project.folder}/${file}.${project.format.video}`
                            : `${project.folder}/${number}.${project.format.video}`;
                        videoElement.controls = true;
                        videoElement.autoplay = true;
                        
                        const closeButton = document.createElement('button');
                        closeButton.className = 'video-close-btn';
                        closeButton.innerHTML = '×';
                        closeButton.onclick = (e) => {
                            e.stopPropagation();
                            videoOverlay.remove();
                            videoElement.pause();
                        };
                        
                        // 添加视频标题
                        const videoTitle = document.createElement('div');
                        videoTitle.className = 'video-title';
                        videoTitle.textContent = typeof file === 'string' ? file : `视频 ${number}`;
                        
                        videoWrapper.appendChild(videoElement);
                        videoWrapper.appendChild(closeButton);
                        videoWrapper.appendChild(videoTitle);
                        videoOverlay.appendChild(videoWrapper);
                        document.body.appendChild(videoOverlay);
                        
                        // 点击背景关闭视频
                        videoOverlay.addEventListener('click', (e) => {
                            if (e.target === videoOverlay) {
                                videoOverlay.remove();
                                videoElement.pause();
                            }
                        });
                    });
                    
                    modalGallery.appendChild(thumbnailContainer);
                } else {
                    // 图片处理保持不变
                    const imgElement = document.createElement('img');
                    tryLoadImage(imgElement, project.folder, number);
                    imgElement.alt = project.title;
                    
                    imgElement.style.cursor = 'pointer';
                    imgElement.addEventListener('click', () => {
                        openImagePreview(imgElement.src);
                    });
                    
                    modalGallery.appendChild(imgElement);
                }
            });

            // 强制重绘
            modal.offsetHeight;

            // 添加 active 类触发动画
            modal.classList.add('active');
            document.body.style.overflow = 'hidden';
            
            // 初始化进度条
            initScrollProgress();
            updateScrollProgress();

            // 更��滚动控制
            const gallery = modalGallery;
            const rightArea = modal.querySelector('.scroll-area.right');
            const leftArea = modal.querySelector('.scroll-area.left');
            
            // 移除所有现有的事件监听器
            const newRightArea = rightArea.cloneNode(true);
            const newLeftArea = leftArea.cloneNode(true);
            rightArea.parentNode.replaceChild(newRightArea, rightArea);
            leftArea.parentNode.replaceChild(newLeftArea, leftArea);

            // 只添加点击快速滚动事件
            newRightArea.onclick = (e) => {
                e.stopPropagation();
                gallery.scrollBy({
                    left: 800,
                    behavior: 'smooth'
                });
                updateScrollProgress();
            };

            newLeftArea.onclick = (e) => {
                e.stopPropagation();
                gallery.scrollBy({
                    left: -800,
                    behavior: 'smooth'
                });
                updateScrollProgress();
            };
        }

        function tryLoadImage(imgElement, folder, number) {
            imgElement.onerror = () => {
                imgElement.src = `${folder}/${number}.jpg`;
                imgElement.onerror = () => {
                    console.error(`Failed to load image: ${folder}/${number}`);
                    imgElement.src = 'default.png';
                }
            };
            imgElement.src = `${folder}/${number}.png`;
        }

        function openImagePreview(imageSrc) {
            const previewModal = document.getElementById('previewModal');
            const previewImage = document.getElementById('previewImage');
            const previewContent = previewModal.querySelector('.preview-content');
            
            // 从点击的图片位置开始动画
            const clickedImage = event.target;
            const rect = clickedImage.getBoundingClientRect();
            previewContent.style.transformOrigin = `${rect.left + rect.width/2}px ${rect.top + rect.height/2}px`;
            
            previewImage.src = imageSrc;
            previewModal.style.display = 'flex';
            previewModal.classList.add('active');
        }

        function closePreview() {
            const previewModal = document.getElementById('previewModal');
            const previewContent = previewModal.querySelector('.preview-content');
            
            previewContent.style.transform = 'scale(0)';
            previewContent.style.opacity = '0';
            
            // 立即隐藏关闭按钮
            previewModal.querySelector('.preview-close').style.display = 'none';

            setTimeout(() => {
                previewModal.classList.remove('active');
                previewModal.style.display = 'none';
                previewContent.style.transform = '';
                previewContent.style.opacity = '';
                rebindModalEvents();
                // 重置关闭按钮显示
                previewModal.querySelector('.preview-close').style.display = '';
            }, 300); // 从 800 改 300
        }

        // 添加重新绑定事件的函数
        function rebindModalEvents() {
            const gallery = modalGallery;
            const rightArea = modal.querySelector('.scroll-area.right');
            const leftArea = modal.querySelector('.scroll-area.left');

            // 只重新绑定点击事件
            rightArea.onclick = (e) => {
                e.stopPropagation();
                gallery.scrollBy({
                    left: 800,
                    behavior: 'smooth'
                });
                updateScrollProgress();
            };

            leftArea.onclick = (e) => {
                e.stopPropagation();
                gallery.scrollBy({
                    left: -800,
                    behavior: 'smooth'
                });
                updateScrollProgress();
            };

            initScrollProgress();
        }

        document.getElementById('previewModal').addEventListener('click', (e) => {
            if (e.target === e.currentTarget) {
                closePreview();
            }
        });

        document.addEventListener('keydown', (e) => {
            if (e.key === 'Escape') {
                closePreview();
                closeModal();
            }
        });

        window.addEventListener('scroll', () => {
            const scrolled = window.scrollY;
            const maxScroll = document.documentElement.scrollHeight - window.innerHeight;
            const scrollPercent = (scrolled / maxScroll) * 100;
            
            const navbar = document.querySelector('.navbar');
            navbar.style.background = `rgba(31, 41, 55, ${Math.min(0.8, scrolled / 500)})`;
        });

        const animateOnScroll = () => {
            const elements = document.querySelectorAll('.fade-up');
            elements.forEach(element => {
                const elementTop = element.getBoundingClientRect().top;
                const elementBottom = element.getBoundingClientRect().bottom;
                const isVisible = elementTop < window.innerHeight && elementBottom >= 0;
                
                if (isVisible) {
                    element.classList.add('visible');
                }
            });
        };

        window.addEventListener('scroll', animateOnScroll);
        window.addEventListener('load', animateOnScroll);

        // 修改关闭模态框函数
        function closeModal() {
            const modalContent = modal.querySelector('.modal-content');
            
            // 立即恢复滚��和点击功能
            document.body.style.overflow = '';
            
            // 开始关闭动画
            modalContent.style.transform = 'scale(0)';
            modalContent.style.opacity = '0';
            modal.style.background = 'rgba(0, 0, 0, 0)';

            // 使用 requestAnimationFrame 确保动画流畅
            requestAnimationFrame(() => {
                setTimeout(() => {
                    modal.classList.remove('active');
                    modal.style.display = 'none';
                    modalContent.style.transform = '';
                    modalContent.style.opacity = '';
                    
                    // 清理内容和事件监���器
                    modalGallery.innerHTML = '';
                    
                    // 重置背景透明度
                    modal.style.background = '';
                }, 300);
            });
        }

        // 点击态框背景关闭
        modal.addEventListener('click', (e) => {
            if (e.target === modal) {
                closeModal();
            }
        });

        // 添加 ESC 键关闭功能
        document.addEventListener('keydown', (e) => {
            if (e.key === 'Escape') {
                closeModal();
                closePreview();
            }
        });

        // 更新图片预览样式
        const styleSheet = document.createElement('style');
        styleSheet.textContent = `
            .modal-gallery img {
                cursor: pointer;
                transition: transform 0.3s ease;
            }
            
            .modal-gallery img:hover {
                transform: scale(1.02);
            }
            
            .preview-modal {
                z-index: 3000;
            }
            
            .preview-content img {
                max-height: 80vh;
                max-width: 80vw;
                object-fit: contain;
            }
        `;
        document.head.appendChild(styleSheet);

        function updateScrollProgress() {
            const gallery = modalGallery;
            const progressBar = document.querySelector('.scroll-progress-bar');
            const scrollHandle = document.querySelector('.scroll-handle');
            
            const scrollPercentage = (gallery.scrollLeft / (gallery.scrollWidth - gallery.clientWidth)) * 100;
            progressBar.style.width = `${scrollPercentage}%`;
        }

        function initScrollProgress() {
            const gallery = modalGallery;
            const progressContainer = document.querySelector('.scroll-progress-container');
            
            // 添加点击跳转功能
            progressContainer.addEventListener('click', (e) => {
                const rect = progressContainer.getBoundingClientRect();
                const percentage = (e.clientX - rect.left) / rect.width;
                const scrollTarget = percentage * (gallery.scrollWidth - gallery.clientWidth);
                
                // 平滑滚动到目标位置
                gallery.scrollTo({
                    left: scrollTarget,
                    behavior: 'smooth'
                });
            });

            // 添加鼠标��动时的视觉反馈
            progressContainer.addEventListener('mousemove', (e) => {
                const rect = progressContainer.getBoundingClientRect();
                const percentage = (e.clientX - rect.left) / rect.width;
                
                // 添加悬停效果
                progressContainer.style.background = 'rgba(255, 255, 255, 0.15)';
                
                // 更新指针样式
                if (e.buttons === 1) { // 如果鼠标按下
                    progressContainer.style.cursor = 'grabbing';
                } else {
                    progressContainer.style.cursor = 'grab';
                }
            });

            progressContainer.addEventListener('mouseleave', () => {
                progressContainer.style.background = 'rgba(255, 255, 255, 0.1)';
            });

            gallery.addEventListener('scroll', updateScrollProgress);
        }

        // 移除原有的点击事件监听，只留头像点击
        const avatarImage = document.querySelector('.hero-content img');
        avatarImage.addEventListener('click', createMultipleFireworks);

        // 分离多烟���和单个烟花的函数
        function createMultipleFireworks(e) {
            e.stopPropagation(); // 阻止事件冒泡，防止触发单个烟花
            for (let i = 0; i < 8; i++) {
                setTimeout(() => {
                    const x = Math.random() * window.innerWidth;
                    const y = Math.random() * (window.innerHeight * 0.7);
                    createSingleFirework(x, y);
                }, i * 200);
            }
        }

        function createSingleFirework(x, y) {
            const firework = document.createElement('div');
            firework.className = 'firework';
            firework.style.left = x + 'px';
            firework.style.top = y + 'px';
            document.body.appendChild(firework);

            const colors = ['#ff0', '#f0f', '#0ff', '#ff4081', '#7c3aed', '#fff'];
            const particleCount = 45;

            for (let i = 0; i < particleCount; i++) {
                const particle = document.createElement('div');
                particle.className = 'firework-particle';
                
                const angle = (i / particleCount) * 360 + Math.random() * 30;
                const distance = 50 + Math.random() * 80;
                const tx = Math.cos(angle * Math.PI / 180) * distance;
                const ty = Math.sin(angle * Math.PI / 180) * distance;
                
                particle.style.background = colors[Math.floor(Math.random() * colors.length)];
                particle.style.setProperty('--tx', `${tx}px`);
                particle.style.setProperty('--ty', `${ty}px`);

                firework.appendChild(particle);
            }

            setTimeout(() => {
                if (document.body.contains(firework)) {
                    document.body.removeChild(firework);
                }
            }, 800);  // 匹配新的动画时长
        }

        // 修改全局点击事件监听
        document.addEventListener('click', (e) => {
            if (!e.target.closest('.modal') && 
                !e.target.closest('.preview-modal') && 
                !e.target.closest('.navbar') &&
                !e.target.closest('button') &&
                !e.target.closest('a') &&
                !e.target.closest('.scroll-area')) {  // 添加对滚动区域的检查
                createSingleFirework(e.clientX, e.clientY);
            }
        });
    </script>
</body>
</html> 
