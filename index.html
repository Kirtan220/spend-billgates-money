<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Spend Bill Gates' Money</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/animate.css/4.1.1/animate.min.css">
    <style>
        :root {
            --primary-color: #007efd;
            --secondary-color: #3498db;
            --success-color: #27ae60;
            --warning-color: #f39c12;
            --danger-color: #e74c3c;
            --light-color: #ecf0f1;
            --dark-color: #2c3e50;
            --background-color: #f5f7fa;
            --card-bg: #ffffff;
            --text-color: #333;
            --text-light: #7f8c8d;
            --shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            --transition: all 0.3s ease;
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: var(--background-color);
            color: var(--text-color);
            line-height: 1.6;
            padding: 20px;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            background-color: var(--card-bg);
            border-radius: 10px;
            box-shadow: var(--shadow);
            overflow: hidden;
        }

        .header {
            padding: 20px;
            text-align: center;
            background: linear-gradient(135deg, var(--primary-color), var(--secondary-color));
            color: white;
        }

        .header h1 {
            margin-bottom: 10px;
            font-size: 2.5rem;
        }

        .money-display {
            margin: 20px 0;
        }

        .money-display h2 {
            font-size: 1.8rem;
            margin-bottom: 10px;
        }

        #money {
            font-weight: bold;
            font-size: 2rem;
        }

        .money-bar {
            height: 20px;
            background-color: var(--light-color);
            border-radius: 10px;
            overflow: hidden;
            margin-top: 10px;
        }

        #money-progress {
            height: 100%;
            width: 100%;
            background: linear-gradient(90deg, var(--success-color), var(--secondary-color));
            transition: width 0.5s ease;
        }

        .main-content {
            padding: 20px;
            display: grid;
            gap: 30px;
            grid-template-columns: 2fr 1fr;
        }

        .items-container {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(280px, 1fr));
            gap: 20px;
        }

        .category {
            background-color: var(--card-bg);
            border-radius: 8px;
            box-shadow: var(--shadow);
            overflow: hidden;
        }

        .category-header {
            background-color: var(--secondary-color);
            color: white;
            padding: 12px 15px;
            font-size: 1.2rem;
        }

        .category-items {
            padding: 15px;
        }

        .item {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 12px 0;
            border-bottom: 1px solid #eee;
            transition: var(--transition);
        }

        .item:last-child {
            border-bottom: none;
        }

        .item:hover {
            transform: translateY(-2px);
        }

        .item-name {
            font-weight: 500;
        }

        .item-price {
            color: var(--primary-color);
            font-weight: bold;
        }

        .btn {
            padding: 8px 15px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            font-weight: bold;
            transition: var(--transition);
        }

        .btn-buy {
            background-color: var(--success-color);
            color: white;
        }

        .btn-buy:hover {
            background-color: #1e8449;
            transform: scale(1.05);
        }

        .btn-buy:disabled {
            background-color: #95a5a6;
            cursor: not-allowed;
            transform: none;
        }

        .purchases {
            background-color: var(--card-bg);
            border-radius: 8px;
            box-shadow: var(--shadow);
            overflow: hidden;
            height: fit-content;
        }

        .purchases-header {
            background-color: var(--primary-color);
            color: white;
            padding: 12px 15px;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        .stats {
            display: flex;
            gap: 15px;
            font-size: 0.9rem;
        }

        .purchases-list {
            padding: 15px;
            max-height: 500px;
            overflow-y: auto;
        }

        .purchase-item {
            padding: 10px 0;
            border-bottom: 1px solid #eee;
            display: flex;
            justify-content: space-between;
        }

        .purchase-item:last-child {
            border-bottom: none;
        }

        .footer {
            padding: 20px;
            display: flex;
            justify-content: center;
            gap: 20px;
            background-color: #f8f9fa;
            border-top: 1px solid #eee;
        }

        .btn-reset {
            background-color: var(--danger-color);
            color: white;
        }

        .btn-undo {
            background-color: var(--warning-color);
            color: white;
        }

        .notification {
            position: fixed;
            bottom: 20px;
            right: 20px;
            padding: 15px 25px;
            border-radius: 5px;
            color: white;
            font-weight: bold;
            box-shadow: var(--shadow);
            z-index: 1000;
            transform: translateX(150%);
            transition: transform 0.3s ease;
        }

        .notification.success {
            background-color: var(--success-color);
        }

        .notification.error {
            background-color: var(--danger-color);
        }

        .notification.warning {
            background-color: var(--warning-color);
        }

        .notification.show {
            transform: translateX(0);
        }

        .hidden {
            display: none;
        }

        @media (max-width: 768px) {
            .main-content {
                grid-template-columns: 1fr;
            }
            
            .header h1 {
                font-size: 2rem;
            }
            
            .footer {
                flex-direction: column;
                align-items: center;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <header class="header">
            <h1 class="animate__animated animate__fadeInDown">Spend Bill Gates' Money</h1>
            <div class="money-display">
                <h2>Remaining: <span id="money">$100,000,000,000</span></h2>
                <div class="money-bar">
                    <div id="money-progress"></div>
                </div>
            </div>
        </header>

        <main class="main-content">
            <div class="items-container" id="items-container">
                <!-- Items will be loaded dynamically from JavaScript -->
            </div>
            
            <div class="purchases">
                <div class="purchases-header">
                    <h3>Your Purchases</h3>
                    <div class="stats">
                        <span id="total-spent">$0 spent</span>
                        <span id="items-bought">0 items</span>
                    </div>
                </div>
                <div id="purchases-list" class="purchases-list"></div>
            </div>
        </main>

        <footer class="footer">
            <button id="reset-btn" class="btn btn-reset">Reset Game</button>
            <button id="undo-btn" class="btn btn-undo" disabled>Undo Last Purchase</button>
        </footer>
    </div>

    <div id="notification" class="notification hidden"></div>

    <script>
        // Game data
        const gameData = {
            initialMoney: 100000000000, // $100 billion
            money: 100000000000,
            purchases: [],
            items: [
                {
                    category: "🏠 Luxury Properties",
                    items: [
                        { name: "Luxury Yacht", price: 10000000 },
                        { name: "Private Jet", price: 150000000 },
                        { name: "Superyacht", price: 250000000 },
                        { name: "Luxury Mansion", price: 50000000 },
                        { name: "Private Island", price: 50000000 },
                        { name: "Penthouse in NYC", price: 30000000 }
                    ]
                },
                {
                    category: "💻 Tech & Business",
                    items: [
                        { name: "Twitter (X)", price: 44000000000 },
                        { name: "Netflix", price: 26000000000 },
                        { name: "NBA Team", price: 8000000000 },
                        { name: "Tech Startup", price: 1000000000 },
                        { name: "AI Company", price: 5000000000 },
                        { name: "SpaceX Shares", price: 2000000000 }
                    ]
                },
                {
                    category: "🛒 Everyday Items",
                    items: [
                        { name: "Cup of Coffee", price: 3 },
                        { name: "Lifetime Pizza Supply", price: 1000000 },
                        { name: "Gold Toilet", price: 50000000 },
                        { name: "Moon Rock", price: 300000000 },
                        { name: "Diamond Watch", price: 500000 },
                        { name: "Sports Car Collection", price: 10000000 }
                    ]
                },
                {
                    category: "❤️ Charity & Causes",
                    items: [
                        { name: "End World Hunger", price: 5000000000 },
                        { name: "Global Education", price: 10000000000 },
                        { name: "Vaccinate Africa", price: 2000000000 },
                        { name: "Build a Hospital", price: 500000000 },
                        { name: "Clean Oceans Initiative", price: 1000000000 },
                        { name: "Wildlife Conservation", price: 800000000 }
                    ]
                }
            ]
        };

        // DOM elements
        const elements = {
            moneyDisplay: document.getElementById('money'),
            moneyProgress: document.getElementById('money-progress'),
            itemsContainer: document.getElementById('items-container'),
            purchasesList: document.getElementById('purchases-list'),
            totalSpent: document.getElementById('total-spent'),
            itemsBought: document.getElementById('items-bought'),
            resetBtn: document.getElementById('reset-btn'),
            undoBtn: document.getElementById('undo-btn'),
            notification: document.getElementById('notification')
        };

        // Utility functions
        const utils = {
            formatMoney: (amount) => {
                return new Intl.NumberFormat('en-US', { 
                    style: 'currency', 
                    currency: 'USD',
                    maximumFractionDigits: 0 
                }).format(amount);
            },
            
            showNotification: (message, type = 'success') => {
                elements.notification.textContent = message;
                elements.notification.className = `notification show ${type}`;
                
                setTimeout(() => {
                    elements.notification.classList.remove('show');
                }, 3000);
            },
            
            animatePurchase: (itemElement) => {
                itemElement.classList.add('animate__animated', 'animate__pulse');
                setTimeout(() => {
                    itemElement.classList.remove('animate__animated', 'animate__pulse');
                }, 1000);
            }
        };

        // Game functions
        const game = {
            init: () => {
                game.renderItems();
                game.updateUI();
                game.setupEventListeners();
            },
            
            renderItems: () => {
                let html = '';
                
                gameData.items.forEach(category => {
                    html += `
                        <div class="category">
                            <div class="category-header">${category.category}</div>
                            <div class="category-items">
                                ${category.items.map(item => `
                                    <div class="item" data-price="${item.price}">
                                        <span class="item-name">${item.name}</span>
                                        <div>
                                            <span class="item-price">${utils.formatMoney(item.price)}</span>
                                            <button class="btn btn-buy" data-name="${item.name}" data-price="${item.price}">
                                                Buy
                                            </button>
                                        </div>
                                    </div>
                                `).join('')}
                            </div>
                        </div>
                    `;
                });
                
                elements.itemsContainer.innerHTML = html;
            },
            
            updateUI: () => {
                // Update money display
                elements.moneyDisplay.textContent = utils.formatMoney(gameData.money);
                
                // Update progress bar
                const progressPercent = (gameData.money / gameData.initialMoney) * 100;
                elements.moneyProgress.style.width = `${progressPercent}%`;
                
                // Update money color based on amount
                if (gameData.money < 1000000000) {
                    elements.moneyDisplay.style.color = 'var(--danger-color)';
                    elements.moneyProgress.style.background = 'var(--danger-color)';
                } else if (gameData.money < 10000000000) {
                    elements.moneyDisplay.style.color = 'var(--warning-color)';
                    elements.moneyProgress.style.background = 'var(--warning-color)';
                } else {
                    elements.moneyDisplay.style.color = 'var(--success-color)';
                    elements.moneyProgress.style.background = 'linear-gradient(90deg, var(--success-color), var(--secondary-color))';
                }
                
                // Update purchases list
                elements.purchasesList.innerHTML = gameData.purchases.map(purchase => `
                    <div class="purchase-item">
                        <span>${purchase.name}</span>
                        <span>${utils.formatMoney(purchase.price)}</span>
                    </div>
                `).join('') || '<div class="empty">No purchases yet</div>';
                
                // Update stats
                const totalSpent = gameData.initialMoney - gameData.money;
                elements.totalSpent.textContent = `${utils.formatMoney(totalSpent)} spent`;
                elements.itemsBought.textContent = `${gameData.purchases.length} items`;
                
                // Update undo button state
                elements.undoBtn.disabled = gameData.purchases.length === 0;
            },
            
            buyItem: (name, price) => {
                if (gameData.money >= price) {
                    gameData.money -= price;
                    gameData.purchases.push({ name, price });
                    game.updateUI();
                    utils.showNotification(`Purchased: ${name}`, 'success');
                    return true;
                } else {
                    utils.showNotification(`Not enough money for ${name}`, 'error');
                    return false;
                }
            },
            
            undoLastPurchase: () => {
                if (gameData.purchases.length > 0) {
                    const lastPurchase = gameData.purchases.pop();
                    gameData.money += lastPurchase.price;
                    game.updateUI();
                    utils.showNotification(`Undo: ${lastPurchase.name}`, 'warning');
                }
            },
            
            resetGame: () => {
                gameData.money = gameData.initialMoney;
                gameData.purchases = [];
                game.updateUI();
                utils.showNotification('Game reset', 'success');
            },
            
            setupEventListeners: () => {
                // Buy buttons
                elements.itemsContainer.addEventListener('click', (e) => {
                    if (e.target.classList.contains('btn-buy')) {
                        const name = e.target.dataset.name;
                        const price = parseInt(e.target.dataset.price);
                        
                        if (game.buyItem(name, price)) {
                            utils.animatePurchase(e.target.closest('.item'));
                        }
                    }
                });
                
                // Reset button
                elements.resetBtn.addEventListener('click', game.resetGame);
                
                // Undo button
                elements.undoBtn.addEventListener('click', game.undoLastPurchase);
            }
        };

        // Initialize the game when DOM is loaded
        document.addEventListener('DOMContentLoaded', game.init);
    </script>
</body>
</html>
