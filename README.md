# Geoserver_SLD-s
Some SLD's I havee been creating for features hosted on our Geoshape instance, via Geoserver. 
Below is an example of what SLD code looks like... 
<pre><code><Rule>
<Name>PI Low - MPI Low</Name>
<Title>PI Low - MPI Low</Title>
<ogc:Filter>
<ogc:PropertyIsEqualTo>
<ogc:PropertyName>Bi_Class</ogc:PropertyName>
<ogc:Literal>A1</ogc:Literal>
</ogc:PropertyIsEqualTo>
</ogc:Filter>
<PolygonSymbolizer>
<Fill>
<CssParameter name="fill">#e8e8e8</CssParameter>
</Fill>
<Stroke>
<CssParameter name="stroke">#000000</CssParameter>
<CssParameter name="stroke-width">0.26</CssParameter>
<CssParameter name="stroke-linejoin">bevel</CssParameter>
</Stroke>
</PolygonSymbolizer>
</Rule></code></pre>
And below is an example of the output... 