# Simple-RTMP-Server

## Usage

<strong>Step 1:</strong> get SRS 

<pre>
git clone https://github.com/ossrs/srs &&
cd srs/trunk
</pre>

<strong>Step 2:</strong> build SRS,
<strong>Requires Centos6.x/Ubuntu12 32/64bits, others see Build([CN][v2_CN_Build],[EN][v2_EN_Build]).</strong>

<pre>
./configure && make
</pre>

<strong>Step 3:</strong> start SRS 

<pre>
./objs/srs -c conf/srs.conf
</pre>
