# R
# R Programming

'hello world'
x = read.csv('C://Users//LENOVO//Downloads//P2-Mispriced-Diamonds.csv',header =TRUE)


#install package ggplot2 for visualization.
install.packages("ggplot2")

ggplot(data=x,aes(x=carat,y=price,color=clarity))+
  geom_point(alpha=0.1)+geom_smooth()

x = 2
typeof(x)
x=c(2)
class(x)
x<-2L
typeof(x)

x<-c(1,2,3)
x<-read.csv(file.choose())
x
t(x)
matplot(t(x))



#qplot
library(ggplot2)
?ggplot2
qplot


# Creating Data Frame
#Execute below code to generate three new vectors
Countries_2012_Dataset <- c("Aruba","Afghanistan","Angola","Albania","United Arab Emirates","Argentina","Armenia","Antigua and Barbuda","Australia","Austria","Azerbaijan","Burundi","Belgium","Benin","Burkina Faso","Bangladesh","Bulgaria","Bahrain","Bahamas, The","Bosnia and Herzegovina","Belarus","Belize","Bermuda","Bolivia","Brazil","Barbados","Brunei Darussalam","Bhutan","Botswana","Central African Republic","Canada","Switzerland","Chile","China","Cote d'Ivoire","Cameroon","Congo, Rep.","Colombia","Comoros","Cabo Verde","Costa Rica","Cuba","Cayman Islands","Cyprus","Czech Republic","Germany","Djibouti","Denmark","Dominican Republic","Algeria","Ecuador","Egypt, Arab Rep.","Eritrea","Spain","Estonia","Ethiopia","Finland","Fiji","France","Micronesia, Fed. Sts.","Gabon","United Kingdom","Georgia","Ghana","Guinea","Gambia, The","Guinea-Bissau","Equatorial Guinea","Greece","Grenada","Greenland","Guatemala","Guam","Guyana","Hong Kong SAR, China","Honduras","Croatia","Haiti","Hungary","Indonesia","India","Ireland","Iran, Islamic Rep.","Iraq","Iceland","Israel","Italy","Jamaica","Jordan","Japan","Kazakhstan","Kenya","Kyrgyz Republic","Cambodia","Kiribati","Korea, Rep.","Kuwait","Lao PDR","Lebanon","Liberia","Libya","St. Lucia","Liechtenstein","Sri Lanka","Lesotho","Lithuania","Luxembourg","Latvia","Macao SAR, China","Morocco","Moldova","Madagascar","Maldives","Mexico","Macedonia, FYR","Mali","Malta","Myanmar","Montenegro","Mongolia","Mozambique","Mauritania","Mauritius","Malawi","Malaysia","Namibia","New Caledonia","Niger","Nigeria","Nicaragua","Netherlands","Norway","Nepal","New Zealand","Oman","Pakistan","Panama","Peru","Philippines","Papua New Guinea","Poland","Puerto Rico","Portugal","Paraguay","French Polynesia","Qatar","Romania","Russian Federation","Rwanda","Saudi Arabia","Sudan","Senegal","Singapore","Solomon Islands","Sierra Leone","El Salvador","Somalia","Serbia","South Sudan","Sao Tome and Principe","Suriname","Slovak Republic","Slovenia","Sweden","Swaziland","Seychelles","Syrian Arab Republic","Chad","Togo","Thailand","Tajikistan","Turkmenistan","Timor-Leste","Tonga","Trinidad and Tobago","Tunisia","Turkey","Tanzania","Uganda","Ukraine","Uruguay","United States","Uzbekistan","St. Vincent and the Grenadines","Venezuela, RB","Virgin Islands (U.S.)","Vietnam","Vanuatu","West Bank and Gaza","Samoa","Yemen, Rep.","South Africa","Congo, Dem. Rep.","Zambia","Zimbabwe")
Codes_2012_Dataset <- c("ABW","AFG","AGO","ALB","ARE","ARG","ARM","ATG","AUS","AUT","AZE","BDI","BEL","BEN","BFA","BGD","BGR","BHR","BHS","BIH","BLR","BLZ","BMU","BOL","BRA","BRB","BRN","BTN","BWA","CAF","CAN","CHE","CHL","CHN","CIV","CMR","COG","COL","COM","CPV","CRI","CUB","CYM","CYP","CZE","DEU","DJI","DNK","DOM","DZA","ECU","EGY","ERI","ESP","EST","ETH","FIN","FJI","FRA","FSM","GAB","GBR","GEO","GHA","GIN","GMB","GNB","GNQ","GRC","GRD","GRL","GTM","GUM","GUY","HKG","HND","HRV","HTI","HUN","IDN","IND","IRL","IRN","IRQ","ISL","ISR","ITA","JAM","JOR","JPN","KAZ","KEN","KGZ","KHM","KIR","KOR","KWT","LAO","LBN","LBR","LBY","LCA","LIE","LKA","LSO","LTU","LUX","LVA","MAC","MAR","MDA","MDG","MDV","MEX","MKD","MLI","MLT","MMR","MNE","MNG","MOZ","MRT","MUS","MWI","MYS","NAM","NCL","NER","NGA","NIC","NLD","NOR","NPL","NZL","OMN","PAK","PAN","PER","PHL","PNG","POL","PRI","PRT","PRY","PYF","QAT","ROU","RUS","RWA","SAU","SDN","SEN","SGP","SLB","SLE","SLV","SOM","SRB","SSD","STP","SUR","SVK","SVN","SWE","SWZ","SYC","SYR","TCD","TGO","THA","TJK","TKM","TLS","TON","TTO","TUN","TUR","TZA","UGA","UKR","URY","USA","UZB","VCT","VEN","VIR","VNM","VUT","PSE","WSM","YEM","ZAF","COD","ZMB","ZWE")
Regions_2012_Dataset <- c("The Americas","Asia","Africa","Europe","Middle East","The Americas","Asia","The Americas","Oceania","Europe","Asia","Africa","Europe","Africa","Africa","Asia","Europe","Middle East","The Americas","Europe","Europe","The Americas","The Americas","The Americas","The Americas","The Americas","Asia","Asia","Africa","Africa","The Americas","Europe","The Americas","Asia","Africa","Africa","Africa","The Americas","Africa","Africa","The Americas","The Americas","The Americas","Europe","Europe","Europe","Africa","Europe","The Americas","Africa","The Americas","Africa","Africa","Europe","Europe","Africa","Europe","Oceania","Europe","Oceania","Africa","Europe","Asia","Africa","Africa","Africa","Africa","Africa","Europe","The Americas","The Americas","The Americas","Oceania","The Americas","Asia","The Americas","Europe","The Americas","Europe","Asia","Asia","Europe","Middle East","Middle East","Europe","Middle East","Europe","The Americas","Middle East","Asia","Asia","Africa","Asia","Asia","Oceania","Asia","Middle East","Asia","Middle East","Africa","Africa","The Americas","Europe","Asia","Africa","Europe","Europe","Europe","Asia","Africa","Europe","Africa","Asia","The Americas","Europe","Africa","Europe","Asia","Europe","Asia","Africa","Africa","Africa","Africa","Asia","Africa","Oceania","Africa","Africa","The Americas","Europe","Europe","Asia","Oceania","Middle East","Asia","The Americas","The Americas","Asia","Oceania","Europe","The Americas","Europe","The Americas","Oceania","Middle East","Europe","Europe","Africa","Middle East","Africa","Africa","Asia","Oceania","Africa","The Americas","Africa","Europe","Africa","Africa","The Americas","Europe","Europe","Europe","Africa","Africa","Middle East","Africa","Africa","Asia","Asia","Asia","Asia","Oceania","The Americas","Africa","Europe","Africa","Africa","Europe","The Americas","The Americas","Asia","The Americas","The Americas","The Americas","Asia","Oceania","Middle East","Oceania","Middle East","Africa","Africa","Africa","Africa")


#(c) Kirill Eremenko, www.superdatascience.com

mydf <- data.frame(Countries_2012_Dataset,Codes_2012_Dataset,Regions_2012_Dataset)
head(mydf)
head(x)
merged <- merge(mydf,x,by.x ="Codes_2012_Dataset",by.y = "Country.Code" )
merged

# Visualizing using qplot-2
qplot(data = merged,x=Internet.users , y=Birth.rate,
      colour=Regions_2012_Dataset,size=I(5),shape=I(10))



#qplot Factors.
movies <- read.csv(file.choose())
movies
head(movies)
str(movies)
summary(movies)

# Converting Non Numeric Factor to Numeric Factor (Year)
summary(movies$Year.of.release)
movies$Year.of.release <- factor(movies$Year.of.release)

summary(movies)


#Aesthatic 
ggplot(data=movies,aes(x=movies$Audience.Ratings..,y=movies$Rotten.Tomatoes.Ratings..))

# Add geometric
ggplot(data=movies,aes(x=movies$Audience.Ratings..,y=movies$Rotten.Tomatoes.Ratings..))+ geom_point()


# Add Colour
ggplot(data=movies,aes(x=Audience.Ratings..,y=Rotten.Tomatoes.Ratings..,colour=Rotten.Tomatoes.Ratings..,size=movies$Audience.Ratings..,alpha=I(0.5),shape=I(15)))+ geom_point()

# Aesthatic
q<-ggplot(data=movies,aes(x=Audience.Ratings..,y=Rotten.Tomatoes.Ratings..,colour=Rotten.Tomatoes.Ratings..,size=movies$Audience.Ratings..))
q # here it wont show any graph representation , since geom is missing
q+geom_point()

#Overriding Aesthetics
q+geom_point(aes(size=movies$Audience.Ratings..))

#ex3 # if you use aes inside the geom_line/geom_point , this is named as Mapping
q+geom_point(aes(x=movies$Audience.Ratings..))+xlab("Budget Millions $$$")


#ex4 # here you cant see aes inside the geom_line/geom_point , this is named as setting.
q+geom_line(size=1)+geom_point()

# Histogram vs Density Chart
s <- ggplot(data=movies,aes(x=movies$Budget..million...))
s+geom_histogram(binwidth = 5)

# Add Colour
s+geom_histogram(binwidth = 5,aes(fill=movies$Genre))

# Set a Border
s+geom_histogram(binwidth = 5,aes(fill=movies$Genre),colour = "Black")

#Density Chart
s+geom_density(aes(fill = movies$Genre))
s+geom_density(aes(fill = movies$Genre),position = 'stack')


# Facets
s+geom_density(aes(fill = movies$Genre),position = 'stack')+facet_grid(movies$Genre~.)
s+geom_density(aes(fill = movies$Genre),position = 'stack')+facet_grid(movies$Genre~movies$Year.of.release)


# Coordinates.
#1). Limits
q<-ggplot(data=movies,aes(x=Audience.Ratings..,y=Rotten.Tomatoes.Ratings..,colour=Rotten.Tomatoes.Ratings..,size=movies$Audience.Ratings..))
q+geom_point()+xlim(50,100)
+ylim(50,100)# Here limiting some particular higher range values.
# but ylim, xlim wont work in histogram.

#2). Zoom #here zoom operation took place for the particular area
s <- ggplot(data=movies,aes(x=movies$Budget..million...))
s+geom_histogram(binwidth = 5)+coord_cartesian(xlim = c(0,50))


norm
#practice
counter <- 0
for (i in rnorm(100)) {
  if(i>-1 & i<1){
    counter = counter+1
  }
  
}
counter

#HomeWork Section-5
data <- read.csv(file.choose())
data
head(data)
tail(data)
str(data)
summary(data)

#insight into next session
data$Year
factor <- factor(data$Year)
factor
levels(factor)

#filter into Data Frame
data1960 <- data[data$Year==1960,]
data2013 <- data[data$Year==2013,]

# to check row count
nrow(data1960)
nrow(data2013)

# Create an additional DataFrame
add1960 <- data.frame(Country = data$Country.Code,Life_Exp = data1960)
add2013 <- data.frame(Country = data$Country.Code,Life_Exp = data2013)


# Homework sction6
datas <- read.csv(file.choose())
datas


f <- function(vector=1:3){
  vector*5
}
f()+f(c(1,1,1))
