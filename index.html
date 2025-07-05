<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>BlueVPS - Enterprise VPS Hosting Solutions</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
    <script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
    <link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet">
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css" rel="stylesheet">
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        primary: '#5D5CDE',
                        'primary-dark': '#4A49C7',
                        'primary-light': '#7B7AE8'
                    },
                    animation: {
                        'fade-in-up': 'fadeInUp 0.6s ease-out',
                        'bounce-slow': 'bounce 2s infinite',
                        'pulse-slow': 'pulse 3s infinite',
                        'float': 'float 3s ease-in-out infinite',
                        'gradient': 'gradient 3s ease infinite',
                    },
                    keyframes: {
                        fadeInUp: {
                            '0%': { opacity: '0', transform: 'translateY(30px)' },
                            '100%': { opacity: '1', transform: 'translateY(0)' },
                        },
                        float: {
                            '0%, 100%': { transform: 'translateY(0px)' },
                            '50%': { transform: 'translateY(-10px)' },
                        },
                        gradient: {
                            '0%, 100%': { backgroundPosition: '0% 50%' },
                            '50%': { backgroundPosition: '100% 50%' },
                        }
                    }
                }
            }
        }
    </script>
    <style>
        .gradient-bg {
            background: linear-gradient(-45deg, #5D5CDE, #4A49C7, #7B7AE8, #5D5CDE);
            background-size: 400% 400%;
            animation: gradient 15s ease infinite;
        }
        .glass-effect {
            background: rgba(255, 255, 255, 0.1);
            backdrop-filter: blur(10px);
            border: 1px solid rgba(255, 255, 255, 0.2);
        }
        .card-hover {
            transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1);
        }
        .card-hover:hover {
            transform: translateY(-12px) scale(1.02);
            box-shadow: 0 25px 50px rgba(93, 92, 222, 0.3);
        }
        .tech-grid {
            background-image: 
                linear-gradient(rgba(93, 92, 222, 0.1) 1px, transparent 1px),
                linear-gradient(90deg, rgba(93, 92, 222, 0.1) 1px, transparent 1px);
            background-size: 20px 20px;
        }
        .status-pulse {
            animation: pulse 2s cubic-bezier(0.4, 0, 0.6, 1) infinite;
        }
        .typing-animation::after {
            content: '|';
            animation: blink 1s infinite;
        }
        @keyframes blink {
            0%, 50% { opacity: 1; }
            51%, 100% { opacity: 0; }
        }
        .server-ping {
            position: relative;
            display: inline-block;
        }
        .server-ping::before {
            content: '';
            position: absolute;
            top: 50%;
            left: 50%;
            width: 100%;
            height: 100%;
            border-radius: 50%;
            background: #10B981;
            transform: translate(-50%, -50%);
            animation: ping 2s cubic-bezier(0, 0, 0.2, 1) infinite;
        }
        .code-block {
            background: #1a1a1a;
            border-radius: 8px;
            padding: 1rem;
            font-family: 'Courier New', monospace;
            color: #10B981;
            overflow-x: auto;
        }
    </style>
</head>
<body class="bg-white dark:bg-gray-900 text-gray-900 dark:text-white transition-all duration-300">

    <!-- Live Chat Widget -->
    <div id="chatWidget" class="fixed bottom-4 right-4 z-50">
        <div id="chatButton" onclick="toggleChat()" class="bg-primary hover:bg-primary-dark text-white p-4 rounded-full shadow-lg cursor-pointer card-hover">
            <i class="fas fa-comments text-xl"></i>
            <span id="chatNotification" class="absolute -top-2 -right-2 bg-red-500 text-white text-xs rounded-full w-6 h-6 flex items-center justify-center">3</span>
        </div>
        
        <div id="chatBox" class="hidden absolute bottom-16 right-0 w-80 h-96 bg-white dark:bg-gray-800 rounded-lg shadow-2xl border">
            <div class="bg-primary text-white p-4 rounded-t-lg">
                <div class="flex items-center justify-between">
                    <div class="flex items-center space-x-2">
                        <div class="w-3 h-3 bg-green-400 rounded-full status-pulse"></div>
                        <span class="font-semibold">Live Support</span>
                    </div>
                    <button onclick="toggleChat()" class="text-white hover:text-gray-200">
                        <i class="fas fa-times"></i>
                    </button>
                </div>
            </div>
            <div class="p-4 h-64 overflow-y-auto">
                <div class="space-y-3">
                    <div class="bg-gray-100 dark:bg-gray-700 p-3 rounded-lg">
                        <p class="text-sm">👋 Hi! How can I help you with your VPS hosting needs today?</p>
                    </div>
                    <div class="bg-blue-100 dark:bg-blue-900 p-3 rounded-lg ml-8">
                        <p class="text-sm">I need help choosing a plan</p>
                    </div>
                    <div class="bg-gray-100 dark:bg-gray-700 p-3 rounded-lg">
                        <p class="text-sm">I'd be happy to help! What's your expected traffic and resource needs?</p>
                    </div>
                </div>
            </div>
            <div class="p-4 border-t dark:border-gray-600">
                <div class="flex space-x-2">
                    <input type="text" placeholder="Type your message..." class="flex-1 border rounded-lg px-3 py-2 text-base focus:outline-none focus:border-primary dark:bg-gray-700 dark:border-gray-600">
                    <button class="bg-primary text-white px-4 py-2 rounded-lg hover:bg-primary-dark">
                        <i class="fas fa-paper-plane"></i>
                    </button>
                </div>
            </div>
        </div>
    </div>

    <!-- Navigation -->
    <nav class="bg-white/90 dark:bg-gray-900/90 backdrop-blur-md shadow-lg sticky top-0 z-40">
        <div class="container mx-auto px-4">
            <div class="flex items-center justify-between py-4">
                <div class="flex items-center space-x-3">
                    <div class="w-12 h-12 gradient-bg rounded-xl flex items-center justify-center">
                        <i class="fas fa-server text-white text-xl"></i>
                    </div>
                    <div>
                        <h1 class="text-2xl font-bold text-primary">BlueVPS</h1>
                        <p class="text-xs text-gray-500">Enterprise Hosting</p>
                    </div>
                </div>
                
                <div class="hidden lg:flex items-center space-x-8">
                    <a href="#home" class="hover:text-primary transition-colors">Home</a>
                    <a href="#plans" class="hover:text-primary transition-colors">Plans</a>
                    <a href="#features" class="hover:text-primary transition-colors">Features</a>
                    <a href="#locations" class="hover:text-primary transition-colors">Locations</a>
                    <a href="#dashboard" class="hover:text-primary transition-colors">Dashboard</a>
                    <a href="#support" class="hover:text-primary transition-colors">Support</a>
                </div>

                <div class="flex items-center space-x-4">
                    <div class="hidden md:flex items-center space-x-2 bg-green-100 dark:bg-green-900 px-3 py-1 rounded-full">
                        <div class="w-2 h-2 bg-green-500 rounded-full status-pulse"></div>
                        <span class="text-sm text-green-700 dark:text-green-300">All Systems Operational</span>
                    </div>
                    <button id="mobileMenu" class="lg:hidden text-2xl">
                        <i class="fas fa-bars"></i>
                    </button>
                </div>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section id="home" class="relative overflow-hidden">
        <div class="absolute inset-0 tech-grid opacity-20"></div>
        <div class="gradient-bg py-24 relative">
            <div class="container mx-auto px-4">
                <div class="grid lg:grid-cols-2 gap-12 items-center">
                    <div data-aos="fade-right">
                        <div class="inline-flex items-center bg-white/20 px-4 py-2 rounded-full mb-6">
                            <i class="fas fa-award text-yellow-400 mr-2"></i>
                            <span class="text-white text-sm">Award-Winning Infrastructure</span>
                        </div>
                        <h1 class="text-5xl lg:text-7xl font-bold text-white mb-6">
                            Next-Gen <span class="text-yellow-400">VPS</span> Hosting
                        </h1>
                        <p class="text-xl text-blue-100 mb-8 leading-relaxed">
                            Deploy lightning-fast virtual servers with enterprise-grade security, 
                            99.99% uptime SLA, and global edge locations. Scale instantly with our 
                            AI-powered infrastructure.
                        </p>
                        <div class="flex flex-col sm:flex-row gap-4 mb-8">
                            <button onclick="scrollToPlans()" class="bg-white text-primary px-8 py-4 rounded-xl font-bold hover:bg-gray-100 transition-all transform hover:scale-105">
                                <i class="fas fa-rocket mr-2"></i>Start Free Trial
                            </button>
                            <button onclick="showServerSelector()" class="glass-effect text-white px-8 py-4 rounded-xl font-bold hover:bg-white/20 transition-all">
                                <i class="fas fa-globe mr-2"></i>View Live Demo
                            </button>
                        </div>
                        
                        <!-- Real-time Stats -->
                        <div class="grid grid-cols-3 gap-4">
                            <div class="glass-effect p-4 rounded-xl text-center">
                                <div class="text-2xl font-bold text-white" id="activeServers">12,847</div>
                                <div class="text-blue-200 text-sm">Active Servers</div>
                            </div>
                            <div class="glass-effect p-4 rounded-xl text-center">
                                <div class="text-2xl font-bold text-white">99.99%</div>
                                <div class="text-blue-200 text-sm">Uptime SLA</div>
                            </div>
                            <div class="glass-effect p-4 rounded-xl text-center">
                                <div class="text-2xl font-bold text-white" id="responseTime">12ms</div>
                                <div class="text-blue-200 text-sm">Avg Response</div>
                            </div>
                        </div>
                    </div>
                    
                    <div class="relative" data-aos="fade-left">
                        <!-- 3D Server Visualization -->
                        <div class="relative w-full h-96 bg-gradient-to-br from-gray-800 to-gray-900 rounded-2xl overflow-hidden">
                            <div class="absolute inset-0 bg-gradient-to-t from-primary/20 to-transparent"></div>
                            <div class="relative z-10 p-8 h-full flex flex-col justify-between">
                                <div>
                                    <h3 class="text-white text-xl font-bold mb-4">Server Dashboard</h3>
                                    <div class="space-y-3">
                                        <div class="flex justify-between items-center">
                                            <span class="text-gray-300">CPU Usage</span>
                                            <span class="text-green-400">23%</span>
                                        </div>
                                        <div class="w-full bg-gray-700 rounded-full h-2">
                                            <div class="bg-green-400 h-2 rounded-full w-1/4 animate-pulse"></div>
                                        </div>
                                        
                                        <div class="flex justify-between items-center">
                                            <span class="text-gray-300">RAM Usage</span>
                                            <span class="text-blue-400">45%</span>
                                        </div>
                                        <div class="w-full bg-gray-700 rounded-full h-2">
                                            <div class="bg-blue-400 h-2 rounded-full w-2/5 animate-pulse"></div>
                                        </div>
                                        
                                        <div class="flex justify-between items-center">
                                            <span class="text-gray-300">Network I/O</span>
                                            <span class="text-purple-400">67%</span>
                                        </div>
                                        <div class="w-full bg-gray-700 rounded-full h-2">
                                            <div class="bg-purple-400 h-2 rounded-full w-2/3 animate-pulse"></div>
                                        </div>
                                    </div>
                                </div>
                                
                                <div class="bg-gray-800/50 rounded-lg p-4">
                                    <div class="flex items-center justify-between mb-2">
                                        <span class="text-gray-300 text-sm">Live Terminal</span>
                                        <div class="flex space-x-1">
                                            <div class="w-3 h-3 bg-red-500 rounded-full"></div>
                                            <div class="w-3 h-3 bg-yellow-500 rounded-full"></div>
                                            <div class="w-3 h-3 bg-green-500 rounded-full"></div>
                                        </div>
                                    </div>
                                    <div class="code-block text-sm">
                                        <div>$ systemctl status nginx</div>
                                        <div class="text-green-400">● nginx.service - running</div>
                                        <div class="typing-animation">$ </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Server Location Selector Modal -->
    <div id="serverModal" class="fixed inset-0 bg-black/50 backdrop-blur-sm hidden items-center justify-center z-50">
        <div class="bg-white dark:bg-gray-800 rounded-2xl p-8 max-w-4xl w-full mx-4 max-h-[80vh] overflow-y-auto">
            <div class="flex justify-between items-center mb-6">
                <h3 class="text-2xl font-bold">Choose Your Server Location</h3>
                <button onclick="hideServerSelector()" class="text-gray-500 hover:text-gray-700">
                    <i class="fas fa-times text-xl"></i>
                </button>
            </div>
            
            <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-4">
                <div class="location-card bg-gradient-to-br from-blue-50 to-blue-100 dark:from-blue-900/20 dark:to-blue-800/20 p-6 rounded-xl cursor-pointer hover:shadow-lg transition-all">
                    <div class="flex items-center justify-between mb-4">
                        <div class="flex items-center space-x-2">
                            <i class="fas fa-server text-blue-600"></i>
                            <span class="font-semibold">New York, USA</span>
                        </div>
                        <div class="server-ping w-3 h-3 bg-green-500 rounded-full"></div>
                    </div>
                    <div class="space-y-2 text-sm">
                        <div class="flex justify-between">
                            <span>Ping:</span>
                            <span class="text-green-600 font-semibold">12ms</span>
                        </div>
                        <div class="flex justify-between">
                            <span>Load:</span>
                            <span class="text-green-600 font-semibold">Low</span>
                        </div>
                        <div class="flex justify-between">
                            <span>Available:</span>
                            <span class="text-green-600 font-semibold">✓</span>
                        </div>
                    </div>
                </div>
                
                <div class="location-card bg-gradient-to-br from-green-50 to-green-100 dark:from-green-900/20 dark:to-green-800/20 p-6 rounded-xl cursor-pointer hover:shadow-lg transition-all">
                    <div class="flex items-center justify-between mb-4">
                        <div class="flex items-center space-x-2">
                            <i class="fas fa-server text-green-600"></i>
                            <span class="font-semibold">London, UK</span>
                        </div>
                        <div class="server-ping w-3 h-3 bg-green-500 rounded-full"></div>
                    </div>
                    <div class="space-y-2 text-sm">
                        <div class="flex justify-between">
                            <span>Ping:</span>
                            <span class="text-green-600 font-semibold">8ms</span>
                        </div>
                        <div class="flex justify-between">
                            <span>Load:</span>
                            <span class="text-green-600 font-semibold">Low</span>
                        </div>
                        <div class="flex justify-between">
                            <span>Available:</span>
                            <span class="text-green-600 font-semibold">✓</span>
                        </div>
                    </div>
                </div>
                
                <div class="location-card bg-gradient-to-br from-purple-50 to-purple-100 dark:from-purple-900/20 dark:to-purple-800/20 p-6 rounded-xl cursor-pointer hover:shadow-lg transition-all">
                    <div class="flex items-center justify-between mb-4">
                        <div class="flex items-center space-x-2">
                            <i class="fas fa-server text-purple-600"></i>
                            <span class="font-semibold">Tokyo, Japan</span>
                        </div>
                        <div class="server-ping w-3 h-3 bg-green-500 rounded-full"></div>
                    </div>
                    <div class="space-y-2 text-sm">
                        <div class="flex justify-between">
                            <span>Ping:</span>
                            <span class="text-green-600 font-semibold">15ms</span>
                        </div>
                        <div class="flex justify-between">
                            <span>Load:</span>
                            <span class="text-yellow-600 font-semibold">Medium</span>
                        </div>
                        <div class="flex justify-between">
                            <span>Available:</span>
                            <span class="text-green-600 font-semibold">✓</span>
                        </div>
                    </div>
                </div>
                
                <div class="location-card bg-gradient-to-br from-red-50 to-red-100 dark:from-red-900/20 dark:to-red-800/20 p-6 rounded-xl cursor-pointer hover:shadow-lg transition-all">
                    <div class="flex items-center justify-between mb-4">
                        <div class="flex items-center space-x-2">
                            <i class="fas fa-server text-red-600"></i>
                            <span class="font-semibold">Sydney, AU</span>
                        </div>
                        <div class="server-ping w-3 h-3 bg-green-500 rounded-full"></div>
                    </div>
                    <div class="space-y-2 text-sm">
                        <div class="flex justify-between">
                            <span>Ping:</span>
                            <span class="text-green-600 font-semibold">18ms</span>
                        </div>
                        <div class="flex justify-between">
                            <span>Load:</span>
                            <span class="text-green-600 font-semibold">Low</span>
                        </div>
                        <div class="flex justify-between">
                            <span>Available:</span>
                            <span class="text-green-600 font-semibold">✓</span>
                        </div>
                    </div>
                </div>
                
                <div class="location-card bg-gradient-to-br from-yellow-50 to-yellow-100 dark:from-yellow-900/20 dark:to-yellow-800/20 p-6 rounded-xl cursor-pointer hover:shadow-lg transition-all">
                    <div class="flex items-center justify-between mb-4">
                        <div class="flex items-center space-x-2">
                            <i class="fas fa-server text-yellow-600"></i>
                            <span class="font-semibold">Frankfurt, DE</span>
                        </div>
                        <div class="server-ping w-3 h-3 bg-green-500 rounded-full"></div>
                    </div>
                    <div class="space-y-2 text-sm">
                        <div class="flex justify-between">
                            <span>Ping:</span>
                            <span class="text-green-600 font-semibold">10ms</span>
                        </div>
                        <div class="flex justify-between">
                            <span>Load:</span>
                            <span class="text-green-600 font-semibold">Low</span>
                        </div>
                        <div class="flex justify-between">
                            <span>Available:</span>
                            <span class="text-green-600 font-semibold">✓</span>
                        </div>
                    </div>
                </div>
                
                <div class="location-card bg-gradient-to-br from-indigo-50 to-indigo-100 dark:from-indigo-900/20 dark:to-indigo-800/20 p-6 rounded-xl cursor-pointer hover:shadow-lg transition-all">
                    <div class="flex items-center justify-between mb-4">
                        <div class="flex items-center space-x-2">
                            <i class="fas fa-server text-indigo-600"></i>
                            <span class="font-semibold">Singapore</span>
                        </div>
                        <div class="server-ping w-3 h-3 bg-green-500 rounded-full"></div>
                    </div>
                    <div class="space-y-2 text-sm">
                        <div class="flex justify-between">
                            <span>Ping:</span>
                            <span class="text-green-600 font-semibold">14ms</span>
                        </div>
                        <div class="flex justify-between">
                            <span>Load:</span>
                            <span class="text-green-600 font-semibold">Low</span>
                        </div>
                        <div class="flex justify-between">
                            <span>Available:</span>
                            <span class="text-green-600 font-semibold">✓</span>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <!-- Interactive Pricing Calculator -->
    <section class="py-20 bg-gray-50 dark:bg-gray-800">
        <div class="container mx-auto px-4">
            <div class="text-center mb-16" data-aos="fade-up">
                <h2 class="text-4xl font-bold mb-4">Smart Pricing Calculator</h2>
                <p class="text-gray-600 dark:text-gray-400">Configure your perfect VPS and see real-time pricing</p>
            </div>
            
            <div class="max-w-6xl mx-auto">
                <div class="grid lg:grid-cols-2 gap-12">
                    <!-- Configuration Panel -->
                    <div class="bg-white dark:bg-gray-700 rounded-2xl p-8 shadow-lg" data-aos="fade-right">
                        <h3 class="text-2xl font-bold mb-6">Configure Your VPS</h3>
                        
                        <div class="space-y-6">
                            <!-- CPU Slider -->
                            <div>
                                <label class="block text-sm font-semibold mb-2">CPU Cores: <span id="cpuValue">2</span></label>
                                <input type="range" id="cpuSlider" min="1" max="16" value="2" class="w-full accent-primary">
                                <div class="flex justify-between text-xs text-gray-500 mt-1">
                                    <span>1 Core</span>
                                    <span>16 Cores</span>
                                </div>
                            </div>
                            
                            <!-- RAM Slider -->
                            <div>
                                <label class="block text-sm font-semibold mb-2">RAM: <span id="ramValue">4</span> GB</label>
                                <input type="range" id="ramSlider" min="1" max="64" value="4" class="w-full accent-primary">
                                <div class="flex justify-between text-xs text-gray-500 mt-1">
                                    <span>1 GB</span>
                                    <span>64 GB</span>
                                </div>
                            </div>
                            
                            <!-- Storage Slider -->
                            <div>
                                <label class="block text-sm font-semibold mb-2">SSD Storage: <span id="storageValue">50</span> GB</label>
                                <input type="range" id="storageSlider" min="20" max="1000" value="50" class="w-full accent-primary">
                                <div class="flex justify-between text-xs text-gray-500 mt-1">
                                    <span>20 GB</span>
                                    <span>1000 GB</span>
                                </div>
                            </div>
                            
                            <!-- Bandwidth Slider -->
                            <div>
                                <label class="block text-sm font-semibold mb-2">Bandwidth: <span id="bandwidthValue">2</span> TB</label>
                                <input type="range" id="bandwidthSlider" min="1" max="20" value="2" class="w-full accent-primary">
                                <div class="flex justify-between text-xs text-gray-500 mt-1">
                                    <span>1 TB</span>
                                    <span>20 TB</span>
                                </div>
                            </div>
                            
                            <!-- Operating System -->
                            <div>
                                <label class="block text-sm font-semibold mb-2">Operating System</label>
                                <select id="osSelect" class="w-full border border-gray-300 dark:border-gray-600 rounded-lg px-4 py-3 bg-white dark:bg-gray-600 text-base">
                                    <option value="ubuntu">Ubuntu 22.04 LTS</option>
                                    <option value="centos">CentOS 8</option>
                                    <option value="debian">Debian 11</option>
                                    <option value="windows">Windows Server 2022 (+$10/month)</option>
                                    <option value="freebsd">FreeBSD 13</option>
                                </select>
                            </div>
                            
                            <!-- Add-ons -->
                            <div>
                                <label class="block text-sm font-semibold mb-2">Add-ons</label>
                                <div class="space-y-2">
                                    <label class="flex items-center">
                                        <input type="checkbox" id="backupAddon" class="accent-primary mr-2">
                                        <span>Daily Backups (+$5/month)</span>
                                    </label>
                                    <label class="flex items-center">
                                        <input type="checkbox" id="monitoringAddon" class="accent-primary mr-2">
                                        <span>Advanced Monitoring (+$3/month)</span>
                                    </label>
                                    <label class="flex items-center">
                                        <input type="checkbox" id="supportAddon" class="accent-primary mr-2">
                                        <span>Priority Support (+$8/month)</span>
                                    </label>
                                </div>
                            </div>
                        </div>
                    </div>
                    
                    <!-- Pricing Display -->
                    <div class="bg-white dark:bg-gray-700 rounded-2xl p-8 shadow-lg" data-aos="fade-left">
                        <h3 class="text-2xl font-bold mb-6">Your Custom Configuration</h3>
                        
                        <div class="space-y-4 mb-8">
                            <div class="flex justify-between">
                                <span>CPU Cores:</span>
                                <span id="displayCpu" class="font-semibold">2 vCores</span>
                            </div>
                            <div class="flex justify-between">
                                <span>RAM:</span>
                                <span id="displayRam" class="font-semibold">4 GB</span>
                            </div>
                            <div class="flex justify-between">
                                <span>Storage:</span>
                                <span id="displayStorage" class="font-semibold">50 GB SSD</span>
                            </div>
                            <div class="flex justify-between">
                                <span>Bandwidth:</span>
                                <span id="displayBandwidth" class="font-semibold">2 TB</span>
                            </div>
                            <div class="flex justify-between">
                                <span>Operating System:</span>
                                <span id="displayOs" class="font-semibold">Ubuntu 22.04 LTS</span>
                            </div>
                        </div>
                        
                        <div class="border-t dark:border-gray-600 pt-6">
                            <div class="flex justify-between text-lg mb-4">
                                <span>Base Price:</span>
                                <span id="basePrice" class="font-semibold">$19.99/month</span>
                            </div>
                            <div id="addonPrices" class="space-y-2 mb-4 text-sm"></div>
                            <div class="flex justify-between text-2xl font-bold text-primary border-t dark:border-gray-600 pt-4">
                                <span>Total:</span>
                                <span id="totalPrice">$19.99/month</span>
                            </div>
                        </div>
                        
                        <div class="mt-8 space-y-4">
                            <button onclick="deployServer()" class="w-full bg-primary text-white py-4 rounded-xl font-bold hover:bg-primary-dark transition-all transform hover:scale-105">
                                <i class="fas fa-rocket mr-2"></i>Deploy Now - 7 Days Free
                            </button>
                            <button onclick="saveConfiguration()" class="w-full border-2 border-primary text-primary py-3 rounded-xl font-bold hover:bg-primary hover:text-white transition-all">
                                <i class="fas fa-save mr-2"></i>Save Configuration
                            </button>
                        </div>
                        
                        <!-- Performance Estimate -->
                        <div class="mt-8 bg-gradient-to-r from-primary/10 to-purple-500/10 p-6 rounded-xl">
                            <h4 class="font-bold mb-4">Performance Estimate</h4>
                            <div class="grid grid-cols-2 gap-4 text-sm">
                                <div>
                                    <div class="text-gray-600 dark:text-gray-400">Estimated Users:</div>
                                    <div id="estimatedUsers" class="font-bold text-lg">~5,000</div>
                                </div>
                                <div>
                                    <div class="text-gray-600 dark:text-gray-400">Benchmark Score:</div>
                                    <div id="benchmarkScore" class="font-bold text-lg">8,500</div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Premium Plans Section -->
    <section id="plans" class="py-20">
        <div class="container mx-auto px-4">
            <div class="text-center mb-16" data-aos="fade-up">
                <h2 class="text-4xl font-bold mb-4">Choose Your Perfect Plan</h2>
                <p class="text-gray-600 dark:text-gray-400 mb-8">Pre-configured plans for every use case</p>
                
                <!-- Billing Toggle -->
                <div class="inline-flex bg-gray-100 dark:bg-gray-700 rounded-xl p-1">
                    <button id="monthlyBtn" onclick="toggleBilling('monthly')" class="px-6 py-2 rounded-lg font-semibold bg-primary text-white">Monthly</button>
                    <button id="yearlyBtn" onclick="toggleBilling('yearly')" class="px-6 py-2 rounded-lg font-semibold text-gray-600 dark:text-gray-400">Yearly (Save 20%)</button>
                </div>
            </div>
            
            <div class="grid md:grid-cols-2 lg:grid-cols-4 gap-8">
                <!-- Starter Plan -->
                <div class="bg-white dark:bg-gray-800 rounded-2xl p-8 shadow-lg card-hover border-2 border-transparent" data-aos="fade-up" data-aos-delay="100">
                    <div class="text-center mb-6">
                        <h3 class="text-2xl font-bold mb-2">Starter</h3>
                        <p class="text-gray-600 dark:text-gray-400 text-sm">Perfect for small projects</p>
                    </div>
                    
                    <div class="text-center mb-8">
                        <div class="text-4xl font-bold text-primary mb-2">
                            <span class="monthly-price">$9.99</span>
                            <span class="yearly-price hidden">$7.99</span>
                            <span class="text-lg text-gray-500">/mo</span>
                        </div>
                        <div class="yearly-save hidden text-green-600 text-sm font-semibold">Save $24/year</div>
                    </div>
                    
                    <ul class="space-y-3 mb-8">
                        <li class="flex items-center"><i class="fas fa-check text-green-500 mr-3"></i>1 vCPU Core</li>
                        <li class="flex items-center"><i class="fas fa-check text-green-500 mr-3"></i>2GB RAM</li>
                        <li class="flex items-center"><i class="fas fa-check text-green-500 mr-3"></i>40GB NVMe SSD</li>
                        <li class="flex items-center"><i class="fas fa-check text-green-500 mr-3"></i>2TB Bandwidth</li>
                        <li class="flex items-center"><i class="fas fa-check text-green-500 mr-3"></i>1 IPv4 + IPv6</li>
                        <li class="flex items-center"><i class="fas fa-check text-green-500 mr-3"></i>99.9% SLA</li>
                        <li class="flex items-center"><i class="fas fa-check text-green-500 mr-3"></i>24/7 Support</li>
                    </ul>
                    
                    <button onclick="selectPlan('Starter', 9.99)" class="w-full bg-gray-100 dark:bg-gray-700 text-gray-900 dark:text-white py-3 rounded-xl font-semibold hover:bg-gray-200 dark:hover:bg-gray-600 transition-all">
                        Choose Plan
                    </button>
                </div>

                <!-- Professional Plan -->
                <div class="bg-white dark:bg-gray-800 rounded-2xl p-8 shadow-xl card-hover border-2 border-primary relative" data-aos="fade-up" data-aos-delay="200">
                    <div class="absolute -top-4 left-1/2 transform -translate-x-1/2 bg-primary text-white px-6 py-2 rounded-full text-sm font-bold">
                        Most Popular
                    </div>
                    
                    <div class="text-center mb-6">
                        <h3 class="text-2xl font-bold mb-2">Professional</h3>
                        <p class="text-gray-600 dark:text-gray-400 text-sm">Great for growing businesses</p>
                    </div>
                    
                    <div class="text-center mb-8">
                        <div class="text-4xl font-bold text-primary mb-2">
                            <span class="monthly-price">$24.99</span>
                            <span class="yearly-price hidden">$19.99</span>
                            <span class="text-lg text-gray-500">/mo</span>
                        </div>
                        <div class="yearly-save hidden text-green-600 text-sm font-semibold">Save $60/year</div>
                    </div>
                    
                    <ul class="space-y-3 mb-8">
                        <li class="flex items-center"><i class="fas fa-check text-green-500 mr-3"></i>2 vCPU Cores</li>
                        <li class="flex items-center"><i class="fas fa-check text-green-500 mr-3"></i>4GB RAM</li>
                        <li class="flex items-center"><i class="fas fa-check text-green-500 mr-3"></i>80GB NVMe SSD</li>
                        <li class="flex items-center"><i class="fas fa-check text-green-500 mr-3"></i>4TB Bandwidth</li>
                        <li class="flex items-center"><i class="fas fa-check text-green-500 mr-3"></i>2 IPv4 + IPv6</li>
                        <li class="flex items-center"><i class="fas fa-check text-green-500 mr-3"></i>99.99% SLA</li>
                        <li class="flex items-center"><i class="fas fa-check text-green-500 mr-3"></i>Free Daily Backups</li>
                        <li class="flex items-center"><i class="fas fa-check text-green-500 mr-3"></i>Priority Support</li>
                    </ul>
                    
                    <button onclick="selectPlan('Professional', 24.99)" class="w-full bg-primary text-white py-3 rounded-xl font-semibold hover:bg-primary-dark transition-all transform hover:scale-105">
                        Choose Plan
                    </button>
                </div>

                <!-- Business Plan -->
                <div class="bg-white dark:bg-gray-800 rounded-2xl p-8 shadow-lg card-hover border-2 border-transparent" data-aos="fade-up" data-aos-delay="300">
                    <div class="text-center mb-6">
                        <h3 class="text-2xl font-bold mb-2">Business</h3>
                        <p class="text-gray-600 dark:text-gray-400 text-sm">For high-traffic applications</p>
                    </div>
                    
                    <div class="text-center mb-8">
                        <div class="text-4xl font-bold text-primary mb-2">
                            <span class="monthly-price">$49.99</span>
                            <span class="yearly-price hidden">$39.99</span>
                            <span class="text-lg text-gray-500">/mo</span>
                        </div>
                        <div class="yearly-save hidden text-green-600 text-sm font-semibold">Save $120/year</div>
                    </div>
                    
                    <ul class="space-y-3 mb-8">
                        <li class="flex items-center"><i class="fas fa-check text-green-500 mr-3"></i>4 vCPU Cores</li>
                        <li class="flex items-center"><i class="fas fa-check text-green-500 mr-3"></i>8GB RAM</li>
                        <li class="flex items-center"><i class="fas fa-check text-green-500 mr-3"></i>160GB NVMe SSD</li>
                        <li class="flex items-center"><i class="fas fa-check text-green-500 mr-3"></i>8TB Bandwidth</li>
                        <li class="flex items-center"><i class="fas fa-check text-green-500 mr-3"></i>3 IPv4 + IPv6</li>
                        <li class="flex items-center"><i class="fas fa-check text-green-500 mr-3"></i>99.99% SLA</li>
                        <li class="flex items-center"><i class="fas fa-check text-green-500 mr-3"></i>Hourly Backups</li>
                        <li class="flex items-center"><i class="fas fa-check text-green-500 mr-3"></i>White-glove Support</li>
                    </ul>
                    
                    <button onclick="selectPlan('Business', 49.99)" class="w-full bg-gray-100 dark:bg-gray-700 text-gray-900 dark:text-white py-3 rounded-xl font-semibold hover:bg-gray-200 dark:hover:bg-gray-600 transition-all">
                        Choose Plan
                    </button>
                </div>

                <!-- Enterprise Plan -->
                <div class="bg-white dark:bg-gray-800 rounded-2xl p-8 shadow-lg card-hover border-2 border-transparent" data-aos="fade-up" data-aos-delay="400">
                    <div class="text-center mb-6">
                        <h3 class="text-2xl font-bold mb-2">Enterprise</h3>
                        <p class="text-gray-600 dark:text-gray-400 text-sm">Maximum performance</p>
                    </div>
                    
                    <div class="text-center mb-8">
                        <div class="text-4xl font-bold text-primary mb-2">
                            <span class="monthly-price">$99.99</span>
                            <span class="yearly-price hidden">$79.99</span>
                            <span class="text-lg text-gray-500">/mo</span>
                        </div>
                        <div class="yearly-save hidden text-green-600 text-sm font-semibold">Save $240/year</div>
                    </div>
                    
                    <ul class="space-y-3 mb-8">
                        <li class="flex items-center"><i class="fas fa-check text-green-500 mr-3"></i>8 vCPU Cores</li>
                        <li class="flex items-center"><i class="fas fa-check text-green-500 mr-3"></i>16GB RAM</li>
                        <li class="flex items-center"><i class="fas fa-check text-green-500 mr-3"></i>320GB NVMe SSD</li>
                        <li class="flex items-center"><i class="fas fa-check text-green-500 mr-3"></i>16TB Bandwidth</li>
                        <li class="flex items-center"><i class="fas fa-check text-green-500 mr-3"></i>5 IPv4 + IPv6</li>
                        <li class="flex items-center"><i class="fas fa-check text-green-500 mr-3"></i>99.99% SLA</li>
                        <li class="flex items-center"><i class="fas fa-check text-green-500 mr-3"></i>Real-time Backups</li>
                        <li class="flex items-center"><i class="fas fa-check text-green-500 mr-3"></i>Dedicated Support</li>
                    </ul>
                    
                    <button onclick="selectPlan('Enterprise', 99.99)" class="w-full bg-gray-100 dark:bg-gray-700 text-gray-900 dark:text-white py-3 rounded-xl font-semibold hover:bg-gray-200 dark:hover:bg-gray-600 transition-all">
                        Choose Plan
                    </button>
                </div>
            </div>
        </div>
    </section>

    <!-- Advanced Features Section -->
    <section id="features" class="py-20 bg-gray-50 dark:bg-gray-800">
        <div class="container mx-auto px-4">
            <div class="text-center mb-16" data-aos="fade-up">
                <h2 class="text-4xl font-bold mb-4">Enterprise-Grade Features</h2>
                <p class="text-gray-600 dark:text-gray-400">Advanced capabilities that set us apart</p>
            </div>
            
            <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-8">
                <div class="bg-white dark:bg-gray-700 rounded-2xl p-8 shadow-lg card-hover" data-aos="fade-up" data-aos-delay="100">
                    <div class="w-16 h-16 bg-gradient-to-br from-blue-500 to-blue-600 rounded-2xl flex items-center justify-center mb-6">
                        <i class="fas fa-tachometer-alt text-white text-2xl"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-4">NVMe SSD Storage</h3>
                    <p class="text-gray-600 dark:text-gray-300 mb-4">Ultra-fast NVMe SSDs deliver up to 10x faster I/O performance than traditional storage.</p>
                    <div class="bg-blue-50 dark:bg-blue-900/20 p-4 rounded-lg">
                        <div class="text-sm text-blue-600 dark:text-blue-400 font-semibold">Performance: 500K+ IOPS</div>
                    </div>
                </div>
                
                <div class="bg-white dark:bg-gray-700 rounded-2xl p-8 shadow-lg card-hover" data-aos="fade-up" data-aos-delay="200">
                    <div class="w-16 h-16 bg-gradient-to-br from-green-500 to-green-600 rounded-2xl flex items-center justify-center mb-6">
                        <i class="fas fa-shield-alt text-white text-2xl"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-4">DDoS Protection</h3>
                    <p class="text-gray-600 dark:text-gray-300 mb-4">Advanced multi-layer DDoS protection with real-time traffic analysis and automatic mitigation.</p>
                    <div class="bg-green-50 dark:bg-green-900/20 p-4 rounded-lg">
                        <div class="text-sm text-green-600 dark:text-green-400 font-semibold">Protection: Up to 10 Tbps</div>
                    </div>
                </div>
                
                <div class="bg-white dark:bg-gray-700 rounded-2xl p-8 shadow-lg card-hover" data-aos="fade-up" data-aos-delay="300">
                    <div class="w-16 h-16 bg-gradient-to-br from-purple-500 to-purple-600 rounded-2xl flex items-center justify-center mb-6">
                        <i class="fas fa-network-wired text-white text-2xl"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-4">Private Networking</h3>
                    <p class="text-gray-600 dark:text-gray-300 mb-4">Secure private networks between your servers with VLAN isolation and encrypted communication.</p>
                    <div class="bg-purple-50 dark:bg-purple-900/20 p-4 rounded-lg">
                        <div class="text-sm text-purple-600 dark:text-purple-400 font-semibold">Speed: 10 Gbps Internal</div>
                    </div>
                </div>
                
                <div class="bg-white dark:bg-gray-700 rounded-2xl p-8 shadow-lg card-hover" data-aos="fade-up" data-aos-delay="400">
                    <div class="w-16 h-16 bg-gradient-to-br from-red-500 to-red-600 rounded-2xl flex items-center justify-center mb-6">
                        <i class="fas fa-backup text-white text-2xl"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-4">Automated Backups</h3>
                    <p class="text-gray-600 dark:text-gray-300 mb-4">Automated incremental backups with point-in-time recovery and cross-region replication.</p>
                    <div class="bg-red-50 dark:bg-red-900/20 p-4 rounded-lg">
                        <div class="text-sm text-red-600 dark:text-red-400 font-semibold">Retention: 30 Days</div>
                    </div>
                </div>
                
                <div class="bg-white dark:bg-gray-700 rounded-2xl p-8 shadow-lg card-hover" data-aos="fade-up" data-aos-delay="500">
                    <div class="w-16 h-16 bg-gradient-to-br from-yellow-500 to-yellow-600 rounded-2xl flex items-center justify-center mb-6">
                        <i class="fas fa-chart-line text-white text-2xl"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-4">Real-time Monitoring</h3>
                    <p class="text-gray-600 dark:text-gray-300 mb-4">Comprehensive monitoring with alerts, performance metrics, and detailed analytics dashboard.</p>
                    <div class="bg-yellow-50 dark:bg-yellow-900/20 p-4 rounded-lg">
                        <div class="text-sm text-yellow-600 dark:text-yellow-400 font-semibold">Updates: Every 5 seconds</div>
                    </div>
                </div>
                
                <div class="bg-white dark:bg-gray-700 rounded-2xl p-8 shadow-lg card-hover" data-aos="fade-up" data-aos-delay="600">
                    <div class="w-16 h-16 bg-gradient-to-br from-indigo-500 to-indigo-600 rounded-2xl flex items-center justify-center mb-6">
                        <i class="fas fa-rocket text-white text-2xl"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-4">One-Click Apps</h3>
                    <p class="text-gray-600 dark:text-gray-300 mb-4">Deploy popular applications instantly with our one-click installation marketplace.</p>
                    <div class="bg-indigo-50 dark:bg-indigo-900/20 p-4 rounded-lg">
                        <div class="text-sm text-indigo-600 dark:text-indigo-400 font-semibold">Apps: 50+ Available</div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Live Dashboard Demo -->
    <section id="dashboard" class="py-20">
        <div class="container mx-auto px-4">
            <div class="text-center mb-16" data-aos="fade-up">
                <h2 class="text-4xl font-bold mb-4">Live Server Dashboard</h2>
                <p class="text-gray-600 dark:text-gray-400">Real-time monitoring and management</p>
            </div>
            
            <div class="max-w-6xl mx-auto">
                <div class="bg-white dark:bg-gray-800 rounded-2xl shadow-2xl overflow-hidden" data-aos="fade-up">
                    <!-- Dashboard Header -->
                    <div class="bg-gradient-to-r from-primary to-primary-dark text-white p-6">
                        <div class="flex items-center justify-between">
                            <div>
                                <h3 class="text-2xl font-bold">Server Dashboard</h3>
                                <p class="opacity-90">srv-ny-001.bluevps.com</p>
                            </div>
                            <div class="flex items-center space-x-4">
                                <div class="flex items-center space-x-2">
                                    <div class="w-3 h-3 bg-green-400 rounded-full status-pulse"></div>
                                    <span>Online</span>
                                </div>
                                <div class="text-right">
                                    <div class="text-sm opacity-90">Uptime</div>
                                    <div class="font-bold">99.98%</div>
                                </div>
                            </div>
                        </div>
                    </div>
                    
                    <!-- Dashboard Content -->
                    <div class="p-6">
                        <div class="grid lg:grid-cols-3 gap-6">
                            <!-- Resource Usage -->
                            <div class="lg:col-span-2">
                                <h4 class="text-lg font-bold mb-4">Resource Usage</h4>
                                <div class="space-y-6">
                                    <!-- CPU Chart -->
                                    <div>
                                        <div class="flex justify-between items-center mb-2">
                                            <span class="font-semibold">CPU Usage</span>
                                            <span id="cpuUsage" class="text-green-600 font-bold">23%</span>
                                        </div>
                                        <div class="relative">
                                            <canvas id="cpuChart" width="400" height="100"></canvas>
                                        </div>
                                    </div>
                                    
                                    <!-- Memory Chart -->
                                    <div>
                                        <div class="flex justify-between items-center mb-2">
                                            <span class="font-semibold">Memory Usage</span>
                                            <span id="memoryUsage" class="text-blue-600 font-bold">45%</span>
                                        </div>
                                        <div class="relative">
                                            <canvas id="memoryChart" width="400" height="100"></canvas>
                                        </div>
                                    </div>
                                    
                                    <!-- Network I/O -->
                                    <div>
                                        <div class="flex justify-between items-center mb-2">
                                            <span class="font-semibold">Network I/O</span>
                                            <span class="text-purple-600 font-bold">1.2 MB/s</span>
                                        </div>
                                        <div class="grid grid-cols-2 gap-4 text-sm">
                                            <div>
                                                <div class="text-gray-600 dark:text-gray-400">Inbound</div>
                                                <div class="font-bold text-green-600">850 KB/s</div>
                                            </div>
                                            <div>
                                                <div class="text-gray-600 dark:text-gray-400">Outbound</div>
                                                <div class="font-bold text-blue-600">350 KB/s</div>
                                            </div>
                                        </div>
                                    </div>
                                </div>
                            </div>
                            
                            <!-- Server Info & Controls -->
                            <div>
                                <h4 class="text-lg font-bold mb-4">Server Controls</h4>
                                <div class="space-y-4">
                                    <div class="grid grid-cols-2 gap-2">
                                        <button class="bg-green-100 hover:bg-green-200 dark:bg-green-900 dark:hover:bg-green-800 text-green-700 dark:text-green-300 px-4 py-2 rounded-lg font-semibold transition-colors">
                                            <i class="fas fa-play mr-1"></i>Start
                                        </button>
                                        <button class="bg-red-100 hover:bg-red-200 dark:bg-red-900 dark:hover:bg-red-800 text-red-700 dark:text-red-300 px-4 py-2 rounded-lg font-semibold transition-colors">
                                            <i class="fas fa-stop mr-1"></i>Stop
                                        </button>
                                        <button class="bg-yellow-100 hover:bg-yellow-200 dark:bg-yellow-900 dark:hover:bg-yellow-800 text-yellow-700 dark:text-yellow-300 px-4 py-2 rounded-lg font-semibold transition-colors">
                                            <i class="fas fa-redo mr-1"></i>Restart
                                        </button>
                                        <button class="bg-blue-100 hover:bg-blue-200 dark:bg-blue-900 dark:hover:bg-blue-800 text-blue-700 dark:text-blue-300 px-4 py-2 rounded-lg font-semibold transition-colors">
                                            <i class="fas fa-terminal mr-1"></i>Console
                                        </button>
                                    </div>
                                    
                                    <div class="bg-gray-50 dark:bg-gray-700 p-4 rounded-lg">
                                        <h5 class="font-semibold mb-2">Quick Stats</h5>
                                        <div class="space-y-2 text-sm">
                                            <div class="flex justify-between">
                                                <span>Disk Usage:</span>
                                                <span class="font-semibold">32% (25.6GB)</span>
                                            </div>
                                            <div class="flex justify-between">
                                                <span>Load Average:</span>
                                                <span class="font-semibold">0.42</span>
                                            </div>
                                            <div class="flex justify-between">
                                                <span>Active Connections:</span>
                                                <span class="font-semibold">127</span>
                                            </div>
                                            <div class="flex justify-between">
                                                <span>Boot Time:</span>
                                                <span class="font-semibold">45s ago</span>
                                            </div>
                                        </div>
                                    </div>
                                    
                                    <div class="bg-blue-50 dark:bg-blue-900/20 p-4 rounded-lg">
                                        <h5 class="font-semibold mb-2 text-blue-700 dark:text-blue-300">Recent Activity</h5>
                                        <div class="space-y-1 text-xs">
                                            <div class="flex justify-between">
                                                <span>SSH Login</span>
                                                <span class="text-gray-500">2m ago</span>
                                            </div>
                                            <div class="flex justify-between">
                                                <span>Backup Completed</span>
                                                <span class="text-gray-500">1h ago</span>
                                            </div>
                                            <div class="flex justify-between">
                                                <span>Package Updated</span>
                                                <span class="text-gray-500">3h ago</span>
                                            </div>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Testimonials Section -->
    <section class="py-20 bg-gray-50 dark:bg-gray-800">
        <div class="container mx-auto px-4">
            <div class="text-center mb-16" data-aos="fade-up">
                <h2 class="text-4xl font-bold mb-4">What Our Customers Say</h2>
                <p class="text-gray-600 dark:text-gray-400">Real feedback from real customers</p>
            </div>
            
            <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-8">
                <div class="bg-white dark:bg-gray-700 rounded-2xl p-8 shadow-lg" data-aos="fade-up" data-aos-delay="100">
                    <div class="flex items-center mb-4">
                        <div class="flex text-yellow-400">
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                        </div>
                        <span class="ml-2 text-gray-600 dark:text-gray-400 text-sm">5.0/5</span>
                    </div>
                    <p class="text-gray-600 dark:text-gray-300 mb-6">"BlueVPS has been incredibly reliable for our e-commerce platform. The performance is outstanding and their support team is always helpful."</p>
                    <div class="flex items-center">
                        <div class="w-12 h-12 bg-gradient-to-br from-blue-400 to-blue-600 rounded-full flex items-center justify-center text-white font-bold">
                            JS
                        </div>
                        <div class="ml-4">
                            <div class="font-semibold">John Smith</div>
                            <div class="text-sm text-gray-500">CEO, TechStore</div>
                        </div>
                    </div>
                </div>
                
                <div class="bg-white dark:bg-gray-700 rounded-2xl p-8 shadow-lg" data-aos="fade-up" data-aos-delay="200">
                    <div class="flex items-center mb-4">
                        <div class="flex text-yellow-400">
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                        </div>
                        <span class="ml-2 text-gray-600 dark:text-gray-400 text-sm">5.0/5</span>
                    </div>
                    <p class="text-gray-600 dark:text-gray-300 mb-6">"Migration to BlueVPS was seamless. The NVMe storage makes our database queries lightning fast. Highly recommended!"</p>
                    <div class="flex items-center">
                        <div class="w-12 h-12 bg-gradient-to-br from-green-400 to-green-600 rounded-full flex items-center justify-center text-white font-bold">
                            MJ
                        </div>
                        <div class="ml-4">
                            <div class="font-semibold">Maria Johnson</div>
                            <div class="text-sm text-gray-500">CTO, DataFlow</div>
                        </div>
                    </div>
                </div>
                
                <div class="bg-white dark:bg-gray-700 rounded-2xl p-8 shadow-lg" data-aos="fade-up" data-aos-delay="300">
                    <div class="flex items-center mb-4">
                        <div class="flex text-yellow-400">
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                        </div>
                        <span class="ml-2 text-gray-600 dark:text-gray-400 text-sm">5.0/5</span>
                    </div>
                    <p class="text-gray-600 dark:text-gray-300 mb-6">"The 99.99% uptime isn't just a promise - it's reality. Our SaaS platform has been rock solid since day one."</p>
                    <div class="flex items-center">
                        <div class="w-12 h-12 bg-gradient-to-br from-purple-400 to-purple-600 rounded-full flex items-center justify-center text-white font-bold">
                            AD
                        </div>
                        <div class="ml-4">
                            <div class="font-semibold">Alex Davis</div>
                            <div class="text-sm text-gray-500">Founder, CloudApp</div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Support Section -->
    <section id="support" class="py-20">
        <div class="container mx-auto px-4">
            <div class="text-center mb-16" data-aos="fade-up">
                <h2 class="text-4xl font-bold mb-4">24/7 Expert Support</h2>
                <p class="text-gray-600 dark:text-gray-400">Get help when you need it most</p>
            </div>
            
            <div class="grid lg:grid-cols-2 gap-12">
                <div data-aos="fade-right">
                    <h3 class="text-2xl font-bold mb-6">Multiple Support Channels</h3>
                    <div class="space-y-6">
                        <div class="flex items-start space-x-4">
                            <div class="w-12 h-12 bg-blue-100 dark:bg-blue-900 rounded-lg flex items-center justify-center">
                                <i class="fas fa-comments text-blue-600 text-xl"></i>
                            </div>
                            <div>
                                <h4 class="font-bold mb-2">Live Chat</h4>
                                <p class="text-gray-600 dark:text-gray-400">Instant support through our live chat system. Average response time: 30 seconds.</p>
                            </div>
                        </div>
                        
                        <div class="flex items-start space-x-4">
                            <div class="w-12 h-12 bg-green-100 dark:bg-green-900 rounded-lg flex items-center justify-center">
                                <i class="fas fa-ticket-alt text-green-600 text-xl"></i>
                            </div>
                            <div>
                                <h4 class="font-bold mb-2">Support Tickets</h4>
                                <p class="text-gray-600 dark:text-gray-400">Detailed technical support through our ticketing system. Response within 1 hour.</p>
                            </div>
                        </div>
                        
                        <div class="flex items-start space-x-4">
                            <div class="w-12 h-12 bg-purple-100 dark:bg-purple-900 rounded-lg flex items-center justify-center">
                                <i class="fas fa-phone text-purple-600 text-xl"></i>
                            </div>
                            <div>
                                <h4 class="font-bold mb-2">Phone Support</h4>
                                <p class="text-gray-600 dark:text-gray-400">Direct phone support for urgent issues. Available 24/7 for Business+ plans.</p>
                            </div>
                        </div>
                        
                        <div class="flex items-start space-x-4">
                            <div class="w-12 h-12 bg-yellow-100 dark:bg-yellow-900 rounded-lg flex items-center justify-center">
                                <i class="fas fa-book text-yellow-600 text-xl"></i>
                            </div>
                            <div>
                                <h4 class="font-bold mb-2">Knowledge Base</h4>
                                <p class="text-gray-600 dark:text-gray-400">Comprehensive documentation and tutorials for self-service support.</p>
                            </div>
                        </div>
                    </div>
                </div>
                
                <div class="bg-white dark:bg-gray-800 rounded-2xl p-8 shadow-lg" data-aos="fade-left">
                    <h3 class="text-2xl font-bold mb-6">Contact Support</h3>
                    <form class="space-y-4">
                        <div>
                            <label class="block text-sm font-semibold mb-2">Name</label>
                            <input type="text" class="w-full border border-gray-300 dark:border-gray-600 rounded-lg px-4 py-3 bg-white dark:bg-gray-700 text-base focus:outline-none focus:border-primary">
                        </div>
                        <div>
                            <label class="block text-sm font-semibold mb-2">Email</label>
                            <input type="email" class="w-full border border-gray-300 dark:border-gray-600 rounded-lg px-4 py-3 bg-white dark:bg-gray-700 text-base focus:outline-none focus:border-primary">
                        </div>
                        <div>
                            <label class="block text-sm font-semibold mb-2">Priority</label>
                            <select class="w-full border border-gray-300 dark:border-gray-600 rounded-lg px-4 py-3 bg-white dark:bg-gray-700 text-base focus:outline-none focus:border-primary">
                                <option>Low - General Question</option>
                                <option>Medium - Technical Issue</option>
                                <option>High - Service Down</option>
                                <option>Critical - Emergency</option>
                            </select>
                        </div>
                        <div>
                            <label class="block text-sm font-semibold mb-2">Message</label>
                            <textarea rows="4" class="w-full border border-gray-300 dark:border-gray-600 rounded-lg px-4 py-3 bg-white dark:bg-gray-700 text-base focus:outline-none focus:border-primary"></textarea>
                        </div>
                        <button type="submit" class="w-full bg-primary text-white py-3 rounded-lg font-semibold hover:bg-primary-dark transition-colors">
                            <i class="fas fa-paper-plane mr-2"></i>Send Message
                        </button>
                    </form>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-900 text-white py-16">
        <div class="container mx-auto px-4">
            <div class="grid md:grid-cols-2 lg:grid-cols-4 gap-8 mb-12">
                <div>
                    <div class="flex items-center space-x-3 mb-6">
                        <div class="w-12 h-12 gradient-bg rounded-xl flex items-center justify-center">
                            <i class="fas fa-server text-white text-xl"></i>
                        </div>
                        <div>
                            <h3 class="text-xl font-bold">BlueVPS</h3>
                            <p class="text-sm text-gray-400">Enterprise Hosting</p>
                        </div>
                    </div>
                    <p class="text-gray-400 mb-6">Leading provider of high-performance VPS hosting solutions with enterprise-grade infrastructure and 24/7 support.</p>
                    <div class="flex space-x-4">
                        <a href="#" class="w-10 h-10 bg-gray-800 rounded-lg flex items-center justify-center hover:bg-primary transition-colors">
                            <i class="fab fa-twitter"></i>
                        </a>
                        <a href="#" class="w-10 h-10 bg-gray-800 rounded-lg flex items-center justify-center hover:bg-primary transition-colors">
                            <i class="fab fa-facebook"></i>
                        </a>
                        <a href="#" class="w-10 h-10 bg-gray-800 rounded-lg flex items-center justify-center hover:bg-primary transition-colors">
                            <i class="fab fa-linkedin"></i>
                        </a>
                        <a href="#" class="w-10 h-10 bg-gray-800 rounded-lg flex items-center justify-center hover:bg-primary transition-colors">
                            <i class="fab fa-github"></i>
                        </a>
                    </div>
                </div>
                
                <div>
                    <h4 class="text-lg font-bold mb-4">Services</h4>
                    <ul class="space-y-2 text-gray-400">
                        <li><a href="#" class="hover:text-white transition-colors">VPS Hosting</a></li>
                        <li><a href="#" class="hover:text-white transition-colors">Dedicated Servers</a></li>
                        <li><a href="#" class="hover:text-white transition-colors">Cloud Hosting</a></li>
                        <li><a href="#" class="hover:text-white transition-colors">Managed Services</a></li>
                        <li><a href="#" class="hover:text-white transition-colors">Domain Registration</a></li>
                    </ul>
                </div>
                
                <div>
                    <h4 class="text-lg font-bold mb-4">Support</h4>
                    <ul class="space-y-2 text-gray-400">
                        <li><a href="#" class="hover:text-white transition-colors">Knowledge Base</a></li>
                        <li><a href="#" class="hover:text-white transition-colors">Server Status</a></li>
                        <li><a href="#" class="hover:text-white transition-colors">Contact Support</a></li>
                        <li><a href="#" class="hover:text-white transition-colors">Network Info</a></li>
                        <li><a href="#" class="hover:text-white transition-colors">Terms of Service</a></li>
                    </ul>
                </div>
                
                <div>
                    <h4 class="text-lg font-bold mb-4">Contact</h4>
                    <div class="space-y-3 text-gray-400">
                        <div class="flex items-center space-x-2">
                            <i class="fas fa-envelope"></i>
                            <span>support@bluevps.com</span>
                        </div>
                        <div class="flex items-center space-x-2">
                            <i class="fas fa-phone"></i>
                            <span>+1 (555) 123-4567</span>
                        </div>
                        <div class="flex items-center space-x-2">
                            <i class="fas fa-map-marker-alt"></i>
                            <span>123 Tech Street, Cloud City</span>
                        </div>
                    </div>
                </div>
            </div>
            
            <div class="border-t border-gray-800 pt-8 text-center">
                <p class="text-gray-400">© 2024 BlueVPS. All rights reserved. | <a href="https://bluevps.com" class="text-primary hover:underline">Visit BlueVPS.com</a></p>
            </div>
        </div>
    </footer>

    <script>
        // Dark mode handling
        if (window.matchMedia && window.matchMedia('(prefers-color-scheme: dark)').matches) {
            document.documentElement.classList.add('dark');
        }
        window.matchMedia('(prefers-color-scheme: dark)').addEventListener('change', event => {
            if (event.matches) {
                document.documentElement.classList.add('dark');
            } else {
                document.documentElement.classList.remove('dark');
            }
        });

        // Initialize AOS
        AOS.init({
            duration: 800,
            once: true,
            offset: 100
        });

        // Live Chat Functions
        function toggleChat() {
            const chatBox = document.getElementById('chatBox');
            const notification = document.getElementById('chatNotification');
            
            if (chatBox.classList.contains('hidden')) {
                chatBox.classList.remove('hidden');
                notification.style.display = 'none';
            } else {
                chatBox.classList.add('hidden');
            }
        }

        // Server Selector Functions
        function showServerSelector() {
            document.getElementById('serverModal').classList.remove('hidden');
            document.getElementById('serverModal').classList.add('flex');
        }

        function hideServerSelector() {
            document.getElementById('serverModal').classList.add('hidden');
            document.getElementById('serverModal').classList.remove('flex');
        }

        // Pricing Calculator
        function updatePricing() {
            const cpu = parseInt(document.getElementById('cpuSlider').value);
            const ram = parseInt(document.getElementById('ramSlider').value);
            const storage = parseInt(document.getElementById('storageSlider').value);
            const bandwidth = parseInt(document.getElementById('bandwidthSlider').value);
            const os = document.getElementById('osSelect').value;
            
            // Update display values
            document.getElementById('cpuValue').textContent = cpu;
            document.getElementById('ramValue').textContent = ram;
            document.getElementById('storageValue').textContent = storage;
            document.getElementById('bandwidthValue').textContent = bandwidth;
            
            document.getElementById('displayCpu').textContent = `${cpu} vCores`;
            document.getElementById('displayRam').textContent = `${ram} GB`;
            document.getElementById('displayStorage').textContent = `${storage} GB SSD`;
            document.getElementById('displayBandwidth').textContent = `${bandwidth} TB`;
            document.getElementById('displayOs').textContent = document.getElementById('osSelect').selectedOptions[0].text;
            
            // Calculate pricing
            let basePrice = cpu * 3 + ram * 2 + storage * 0.1 + bandwidth * 2;
            
            if (os === 'windows') basePrice += 10;
            
            // Add-ons
            let addonPrice = 0;
            let addonText = '';
            
            if (document.getElementById('backupAddon').checked) {
                addonPrice += 5;
                addonText += '<div class="flex justify-between"><span>Daily Backups:</span><span>+$5.00</span></div>';
            }
            if (document.getElementById('monitoringAddon').checked) {
                addonPrice += 3;
                addonText += '<div class="flex justify-between"><span>Advanced Monitoring:</span><span>+$3.00</span></div>';
            }
            if (document.getElementById('supportAddon').checked) {
                addonPrice += 8;
                addonText += '<div class="flex justify-between"><span>Priority Support:</span><span>+$8.00</span></div>';
            }
            
            document.getElementById('addonPrices').innerHTML = addonText;
            document.getElementById('basePrice').textContent = `$${basePrice.toFixed(2)}/month`;
            document.getElementById('totalPrice').textContent = `$${(basePrice + addonPrice).toFixed(2)}/month`;
            
            // Update performance estimates
            const estimatedUsers = Math.floor((cpu * 1000 + ram * 500) * 1.2);
            const benchmarkScore = Math.floor((cpu * 2000 + ram * 100 + storage * 10) * 0.8);
            
            document.getElementById('estimatedUsers').textContent = `~${estimatedUsers.toLocaleString()}`;
            document.getElementById('benchmarkScore').textContent = benchmarkScore.toLocaleString();
        }

        // Billing Toggle
        let currentBilling = 'monthly';
        
        function toggleBilling(type) {
            currentBilling = type;
            const monthlyBtn = document.getElementById('monthlyBtn');
            const yearlyBtn = document.getElementById('yearlyBtn');
            const monthlyPrices = document.querySelectorAll('.monthly-price');
            const yearlyPrices = document.querySelectorAll('.yearly-price');
            const yearlySaves = document.querySelectorAll('.yearly-save');
            
            if (type === 'monthly') {
                monthlyBtn.classList.add('bg-primary', 'text-white');
                monthlyBtn.classList.remove('text-gray-600', 'dark:text-gray-400');
                yearlyBtn.classList.remove('bg-primary', 'text-white');
                yearlyBtn.classList.add('text-gray-600', 'dark:text-gray-400');
                
                monthlyPrices.forEach(el => el.classList.remove('hidden'));
                yearlyPrices.forEach(el => el.classList.add('hidden'));
                yearlySaves.forEach(el => el.classList.add('hidden'));
            } else {
                yearlyBtn.classList.add('bg-primary', 'text-white');
                yearlyBtn.classList.remove('text-gray-600', 'dark:text-gray-400');
                monthlyBtn.classList.remove('bg-primary', 'text-white');
                monthlyBtn.classList.add('text-gray-600', 'dark:text-gray-400');
                
                monthlyPrices.forEach(el => el.classList.add('hidden'));
                yearlyPrices.forEach(el => el.classList.remove('hidden'));
                yearlySaves.forEach(el => el.classList.remove('hidden'));
            }
        }

        // Plan Selection
        function selectPlan(planName, price) {
            if (window.Poe && window.Poe.sendUserMessage) {
                const message = `I'm interested in the ${planName} VPS plan for $${price}/month from BlueVPS. Can you help me get started with the signup process?`;
                window.Poe.sendUserMessage(`@Claude-Sonnet-4 ${message}`, { openChat: true });
            } else {
                // Fallback for when Poe API is not available
                alert(`Selected: ${planName} plan for $${price}/month. Redirecting to BlueVPS.com...`);
                window.open('https://bluevps.com', '_blank');
            }
        }

        function deployServer() {
            if (window.Poe && window.Poe.sendUserMessage) {
                const cpu = document.getElementById('cpuValue').textContent;
                const ram = document.getElementById('ramValue').textContent;
                const storage = document.getElementById('storageValue').textContent;
                const totalPrice = document.getElementById('totalPrice').textContent;
                
                const message = `I want to deploy a custom VPS server with ${cpu} vCPU cores, ${ram}GB RAM, ${storage}GB SSD storage for ${totalPrice}. Can you help me get started with BlueVPS?`;
                window.Poe.sendUserMessage(`@Claude-Sonnet-4 ${message}`, { openChat: true });
            } else {
                alert('Redirecting to BlueVPS.com to complete your custom server deployment...');
                window.open('https://bluevps.com', '_blank');
            }
        }

        function saveConfiguration() {
            const config = {
                cpu: document.getElementById('cpuValue').textContent,
                ram: document.getElementById('ramValue').textContent,
                storage: document.getElementById('storageValue').textContent,
                bandwidth: document.getElementById('bandwidthValue').textContent,
                os: document.getElementById('osSelect').value,
                price: document.getElementById('totalPrice').textContent
            };
            
            // Since localStorage is not available, we'll show a message
            alert('Configuration saved! You can now proceed to BlueVPS.com to complete your order.');
        }

        // Smooth scrolling
        function scrollToPlans() {
            document.getElementById('plans').scrollIntoView({ behavior: 'smooth' });
        }

        // Real-time stats animation
        function animateStats() {
            const servers = document.getElementById('activeServers');
            const responseTime = document.getElementById('responseTime');
            
            setInterval(() => {
                const currentServers = parseInt(servers.textContent.replace(',', ''));
                const newServers = currentServers + Math.floor(Math.random() * 10) - 5;
                servers.textContent = Math.max(12000, newServers).toLocaleString();
                
                const times = ['12ms', '11ms', '13ms', '10ms', '14ms'];
                responseTime.textContent = times[Math.floor(Math.random() * times.length)];
            }, 3000);
        }

        // Dashboard Charts
        function initCharts() {
            // CPU Chart
            const cpuCtx = document.getElementById('cpuChart').getContext('2d');
            const cpuData = Array.from({length: 20}, () => Math.random() * 40 + 10);
            
            new Chart(cpuCtx, {
                type: 'line',
                data: {
                    labels: Array.from({length: 20}, (_, i) => ''),
                    datasets: [{
                        data: cpuData,
                        borderColor: '#10B981',
                        backgroundColor: 'rgba(16, 185, 129, 0.1)',
                        fill: true,
                        tension: 0.4,
                        borderWidth: 2,
                        pointRadius: 0
                    }]
                },
                options: {
                    responsive: true,
                    maintainAspectRatio: false,
                    scales: {
                        x: { display: false },
                        y: { display: false, min: 0, max: 100 }
                    },
                    plugins: { legend: { display: false } },
                    interaction: { intersect: false }
                }
            });

            // Memory Chart
            const memoryCtx = document.getElementById('memoryChart').getContext('2d');
            const memoryData = Array.from({length: 20}, () => Math.random() * 30 + 30);
            
            new Chart(memoryCtx, {
                type: 'line',
                data: {
                    labels: Array.from({length: 20}, (_, i) => ''),
                    datasets: [{
                        data: memoryData,
                        borderColor: '#3B82F6',
                        backgroundColor: 'rgba(59, 130, 246, 0.1)',
                        fill: true,
                        tension: 0.4,
                        borderWidth: 2,
                        pointRadius: 0
                    }]
                },
                options: {
                    responsive: true,
                    maintainAspectRatio: false,
                    scales: {
                        x: { display: false },
                        y: { display: false, min: 0, max: 100 }
                    },
                    plugins: { legend: { display: false } },
                    interaction: { intersect: false }
                }
            });

            // Animate charts
            setInterval(() => {
                const newCpuValue = Math.random() * 40 + 10;
                const newMemoryValue = Math.random() * 30 + 30;
                
                document.getElementById('cpuUsage').textContent = Math.round(newCpuValue) + '%';
                document.getElementById('memoryUsage').textContent = Math.round(newMemoryValue) + '%';
            }, 2000);
        }

        // Event Listeners
        document.addEventListener('DOMContentLoaded', function() {
            // Initialize components
            updatePricing();
            animateStats();
            initCharts();
            
            // Pricing calculator event listeners
            document.getElementById('cpuSlider').addEventListener('input', updatePricing);
            document.getElementById('ramSlider').addEventListener('input', updatePricing);
            document.getElementById('storageSlider').addEventListener('input', updatePricing);
            document.getElementById('bandwidthSlider').addEventListener('input', updatePricing);
            document.getElementById('osSelect').addEventListener('change', updatePricing);
            document.getElementById('backupAddon').addEventListener('change', updatePricing);
            document.getElementById('monitoringAddon').addEventListener('change', updatePricing);
            document.getElementById('supportAddon').addEventListener('change', updatePricing);
            
            console.log('Advanced BlueVPS Platform Loaded');
        });
    </script>

</body>
</html>
