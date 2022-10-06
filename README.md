<h1 align="center">ParkYongGyu/magento2.4.2-php7.4-order</h1>

mkdir ~/docker-magento-install
cd ~/docker-magento-install
git clone https://github.com/ParkYongGyu/magento2.4.2-php7.4-order.git
cd magento2.4.2-php7.4-order.git
rm -rf .git
cd compose
chmod 755 bin/*

curl -s https://raw.githubusercontent.com/ParkYongGyu/magento2.4.2-php7.4-order/main/lib/onelinesetup | bash -s -- 2.4.2 enterprise
