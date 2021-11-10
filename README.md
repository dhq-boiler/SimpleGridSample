# SimpleGridSample

WPFの便利なPanelコントロールを紹介します！

![SimpleGridSample](WebComponents\2021-11-10.png)

## 使い方

RowsプロパティとColumnsプロパティとOrientationを指定するだけ！！！
縦x横＝（Rows, Columns）のグリッドに、Orientationの向きで順番に要素を埋めていってくれます。

```xml
<Window x:Class="SimpleGridSample.MainWindow"
        xmlns="http://schemas.microsoft.com/winfx/2006/xaml/presentation"
        xmlns:x="http://schemas.microsoft.com/winfx/2006/xaml"
        xmlns:d="http://schemas.microsoft.com/expression/blend/2008"
        xmlns:mc="http://schemas.openxmlformats.org/markup-compatibility/2006"
        xmlns:local="clr-namespace:SimpleGridSample"
        mc:Ignorable="d"
        Title="MainWindow"
        SizeToContent="WidthAndHeight">
    <local:SimpleGrid Rows="1" Columns="2" Orientation="Horizontal">
        <Border BorderBrush="Red" BorderThickness="3">
            <local:SimpleGrid Rows="4" Columns="6" Orientation="Vertical">
                <Label>1</Label>
                <Label>2</Label>
                <Label>3</Label>
                <Label>4</Label>
                <Label>5</Label>
                <Label>6</Label>
                <Label>7</Label>
                <Label>8</Label>
                <Label>9</Label>
                <Label>10</Label>
                <Label>11</Label>
                <Label>12</Label>
                <Label>13</Label>
                <Label>14</Label>
                <Label>15</Label>
                <Label>16</Label>
                <Label>17</Label>
                <Label>18</Label>
                <Label>19</Label>
                <Label>20</Label>
                <Label>21</Label>
                <Label>22</Label>
                <Label>23</Label>
                <Label>24</Label>
            </local:SimpleGrid>
        </Border>
        <Border BorderBrush="Blue" BorderThickness="3">
            <local:SimpleGrid Rows="6" Columns="4" Orientation="Horizontal">
                <Label>21</Label>
                <Label>22</Label>
                <Label>23</Label>
                <Label>24</Label>
                <Label>25</Label>
                <Label>26</Label>
                <Label>27</Label>
                <Label>28</Label>
                <Label>29</Label>
                <Label>30</Label>
                <Label>31</Label>
                <Label>32</Label>
                <Label>33</Label>
                <Label>34</Label>
                <Label>35</Label>
                <Label>36</Label>
                <Label>37</Label>
                <Label>38</Label>
                <Label>39</Label>
                <Label>40</Label>
                <Label>40</Label>
                <Label>41</Label>
                <Label>42</Label>
                <Label>43</Label>
            </local:SimpleGrid>
        </Border>
    </local:SimpleGrid>
</Window>

```