# tp2-unqui-uml



[Uploading Diagrama <mxfile host="app.diagrams.net" agent="Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/135.0.0.0 Safari/537.36" version="26.2.14" pages="2">
  <diagram name="Página-1" id="r_VlgksoDCpfUuPQgx2e">
    <mxGraphModel dx="2253" dy="751" grid="1" gridSize="10" guides="1" tooltips="1" connect="1" arrows="1" fold="1" page="1" pageScale="1" pageWidth="827" pageHeight="1169" math="0" shadow="0">
      <root>
        <mxCell id="0" />
        <mxCell id="1" parent="0" />
        <mxCell id="bWU_UAJwaF4-bZPn0_Ai-1" value="Empresa" style="swimlane;fontStyle=1;align=center;verticalAlign=top;childLayout=stackLayout;horizontal=1;startSize=26;horizontalStack=0;resizeParent=1;resizeParentMax=0;resizeLast=0;collapsible=1;marginBottom=0;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="70" y="60" width="370" height="170" as="geometry" />
        </mxCell>
        <mxCell id="bWU_UAJwaF4-bZPn0_Ai-2" value="- nombre: String&lt;div&gt;- cuil: Integer&lt;/div&gt;" style="text;strokeColor=none;fillColor=none;align=left;verticalAlign=top;spacingLeft=4;spacingRight=4;overflow=hidden;rotatable=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;whiteSpace=wrap;html=1;" vertex="1" parent="bWU_UAJwaF4-bZPn0_Ai-1">
          <mxGeometry y="26" width="370" height="34" as="geometry" />
        </mxCell>
        <mxCell id="bWU_UAJwaF4-bZPn0_Ai-3" value="" style="line;strokeWidth=1;fillColor=none;align=left;verticalAlign=middle;spacingTop=-1;spacingLeft=3;spacingRight=3;rotatable=0;labelPosition=right;points=[];portConstraint=eastwest;strokeColor=inherit;" vertex="1" parent="bWU_UAJwaF4-bZPn0_Ai-1">
          <mxGeometry y="60" width="370" height="8" as="geometry" />
        </mxCell>
        <mxCell id="bWU_UAJwaF4-bZPn0_Ai-4" value="+ &lt;u&gt;new(String, Integer, List&amp;lt;Empleado&amp;gt;, Set&amp;lt;ReciboDeHaberes&amp;gt;)&lt;/u&gt;&lt;div&gt;+ totalSueldosBrutos(): Float&lt;/div&gt;&lt;div&gt;+ totalRetenciones(): Float&lt;/div&gt;&lt;div&gt;+ totalSueldosNetos(): Float&amp;nbsp;&lt;/div&gt;&lt;div&gt;+ liquidarSueldos(): void&lt;/div&gt;" style="text;strokeColor=none;fillColor=none;align=left;verticalAlign=top;spacingLeft=4;spacingRight=4;overflow=hidden;rotatable=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;whiteSpace=wrap;html=1;" vertex="1" parent="bWU_UAJwaF4-bZPn0_Ai-1">
          <mxGeometry y="68" width="370" height="102" as="geometry" />
        </mxCell>
        <mxCell id="bWU_UAJwaF4-bZPn0_Ai-5" value="&lt;i&gt;Empleado&lt;/i&gt;" style="swimlane;fontStyle=1;align=center;verticalAlign=top;childLayout=stackLayout;horizontal=1;startSize=26;horizontalStack=0;resizeParent=1;resizeParentMax=0;resizeLast=0;collapsible=1;marginBottom=0;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="790" y="69" width="300" height="280" as="geometry" />
        </mxCell>
        <mxCell id="bWU_UAJwaF4-bZPn0_Ai-6" value="- nombre: String&lt;div&gt;- direccion: String&amp;nbsp;&lt;/div&gt;&lt;div&gt;- estadoCivil: String&lt;/div&gt;&lt;div&gt;- fechaDeNac: LocalDate&lt;/div&gt;&lt;div&gt;- sueldoBasico: Float&lt;/div&gt;" style="text;strokeColor=none;fillColor=none;align=left;verticalAlign=top;spacingLeft=4;spacingRight=4;overflow=hidden;rotatable=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;whiteSpace=wrap;html=1;" vertex="1" parent="bWU_UAJwaF4-bZPn0_Ai-5">
          <mxGeometry y="26" width="300" height="84" as="geometry" />
        </mxCell>
        <mxCell id="bWU_UAJwaF4-bZPn0_Ai-7" value="" style="line;strokeWidth=1;fillColor=none;align=left;verticalAlign=middle;spacingTop=-1;spacingLeft=3;spacingRight=3;rotatable=0;labelPosition=right;points=[];portConstraint=eastwest;strokeColor=inherit;" vertex="1" parent="bWU_UAJwaF4-bZPn0_Ai-5">
          <mxGeometry y="110" width="300" height="8" as="geometry" />
        </mxCell>
        <mxCell id="bWU_UAJwaF4-bZPn0_Ai-8" value="&lt;div&gt;+ &lt;u&gt;new(String, String, String, LocalDate, Float)&lt;/u&gt;&lt;/div&gt;&lt;div&gt;+ getNombre(): String&lt;/div&gt;&lt;div&gt;+ getDireccion(): String&lt;/div&gt;&lt;div&gt;+ getFechaNac(): LocalDate&lt;/div&gt;&lt;div&gt;+ getSueldoBasico(): Float&lt;/div&gt;+ edad(): Integer&lt;div&gt;&lt;i&gt;+ sueldoBruto(): Float&lt;/i&gt;&lt;/div&gt;&lt;div&gt;&lt;i&gt;+ retenciones(): Float&lt;/i&gt;&lt;/div&gt;&lt;div&gt;+ sueldoNeto(): Float&lt;/div&gt;&lt;div&gt;+ &lt;i&gt;infoDesgloceConceptos(): String&lt;/i&gt;&lt;/div&gt;" style="text;strokeColor=none;fillColor=none;align=left;verticalAlign=top;spacingLeft=4;spacingRight=4;overflow=hidden;rotatable=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;whiteSpace=wrap;html=1;" vertex="1" parent="bWU_UAJwaF4-bZPn0_Ai-5">
          <mxGeometry y="118" width="300" height="162" as="geometry" />
        </mxCell>
        <mxCell id="bWU_UAJwaF4-bZPn0_Ai-9" value="empleados" style="endArrow=block;endFill=1;html=1;edgeStyle=orthogonalEdgeStyle;align=left;verticalAlign=top;rounded=0;exitX=1;exitY=0.5;exitDx=0;exitDy=0;entryX=0;entryY=0.5;entryDx=0;entryDy=0;" edge="1" parent="1" source="bWU_UAJwaF4-bZPn0_Ai-4" target="bWU_UAJwaF4-bZPn0_Ai-6">
          <mxGeometry x="-0.4142" y="29" relative="1" as="geometry">
            <mxPoint x="330" y="390" as="sourcePoint" />
            <mxPoint x="490" y="390" as="targetPoint" />
            <mxPoint as="offset" />
          </mxGeometry>
        </mxCell>
        <mxCell id="bWU_UAJwaF4-bZPn0_Ai-10" value="1" style="edgeLabel;resizable=0;html=1;align=left;verticalAlign=bottom;" connectable="0" vertex="1" parent="bWU_UAJwaF4-bZPn0_Ai-9">
          <mxGeometry x="-1" relative="1" as="geometry" />
        </mxCell>
        <mxCell id="bWU_UAJwaF4-bZPn0_Ai-12" value="*" style="edgeLabel;resizable=0;html=1;align=left;verticalAlign=bottom;" connectable="0" vertex="1" parent="1">
          <mxGeometry x="570" y="180" as="geometry">
            <mxPoint x="194" y="-13" as="offset" />
          </mxGeometry>
        </mxCell>
        <mxCell id="bWU_UAJwaF4-bZPn0_Ai-13" value="EmpleadoPermanente" style="swimlane;fontStyle=1;align=center;verticalAlign=top;childLayout=stackLayout;horizontal=1;startSize=26;horizontalStack=0;resizeParent=1;resizeParentMax=0;resizeLast=0;collapsible=1;marginBottom=0;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="500" y="530" width="350" height="260" as="geometry" />
        </mxCell>
        <mxCell id="bWU_UAJwaF4-bZPn0_Ai-14" value="- cantHijos: Integer&lt;div&gt;- antiguedad: Integer&lt;/div&gt;" style="text;strokeColor=none;fillColor=none;align=left;verticalAlign=top;spacingLeft=4;spacingRight=4;overflow=hidden;rotatable=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;whiteSpace=wrap;html=1;" vertex="1" parent="bWU_UAJwaF4-bZPn0_Ai-13">
          <mxGeometry y="26" width="350" height="44" as="geometry" />
        </mxCell>
        <mxCell id="bWU_UAJwaF4-bZPn0_Ai-15" value="" style="line;strokeWidth=1;fillColor=none;align=left;verticalAlign=middle;spacingTop=-1;spacingLeft=3;spacingRight=3;rotatable=0;labelPosition=right;points=[];portConstraint=eastwest;strokeColor=inherit;" vertex="1" parent="bWU_UAJwaF4-bZPn0_Ai-13">
          <mxGeometry y="70" width="350" height="8" as="geometry" />
        </mxCell>
        <mxCell id="bWU_UAJwaF4-bZPn0_Ai-16" value="&lt;div&gt;+ &lt;u&gt;new(String, String, String, LocalDate, Float, Integer, Integer)&lt;/u&gt;&lt;/div&gt;&lt;div&gt;&lt;div&gt;- getCantHijos(): Integer&lt;/div&gt;&lt;div&gt;- getAntiguedad(): Integer&lt;/div&gt;&lt;/div&gt;- sueldoBruto(): Float&lt;div&gt;- retenciones(): Float&lt;/div&gt;&lt;div&gt;- salarioFamiliar(): Float&amp;nbsp;&lt;/div&gt;&lt;div&gt;- pagoAsignacionPorHijo(): Float&amp;nbsp;&lt;/div&gt;&lt;div&gt;- pagoAsignacionPorConyuge(): Float&lt;/div&gt;&lt;div&gt;- pagoAntiguedad(): Float&lt;/div&gt;&lt;div&gt;- retencionesObraSocial(): Float&lt;/div&gt;&lt;div&gt;- retencionesAportesJubilatorios(): Float&amp;nbsp;&amp;nbsp;&lt;/div&gt;&lt;div&gt;-&amp;nbsp;infoDesgloceConceptos(): String&lt;/div&gt;" style="text;strokeColor=none;fillColor=none;align=left;verticalAlign=top;spacingLeft=4;spacingRight=4;overflow=hidden;rotatable=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;whiteSpace=wrap;html=1;" vertex="1" parent="bWU_UAJwaF4-bZPn0_Ai-13">
          <mxGeometry y="78" width="350" height="182" as="geometry" />
        </mxCell>
        <mxCell id="bWU_UAJwaF4-bZPn0_Ai-17" value="EmpleadoTemporario" style="swimlane;fontStyle=1;align=center;verticalAlign=top;childLayout=stackLayout;horizontal=1;startSize=26;horizontalStack=0;resizeParent=1;resizeParentMax=0;resizeLast=0;collapsible=1;marginBottom=0;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="910" y="530" width="380" height="210" as="geometry" />
        </mxCell>
        <mxCell id="bWU_UAJwaF4-bZPn0_Ai-18" value="- fechaFinDesignacion: LocalDate&lt;div&gt;- cantHorasExtras: Integer&lt;/div&gt;" style="text;strokeColor=none;fillColor=none;align=left;verticalAlign=top;spacingLeft=4;spacingRight=4;overflow=hidden;rotatable=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;whiteSpace=wrap;html=1;" vertex="1" parent="bWU_UAJwaF4-bZPn0_Ai-17">
          <mxGeometry y="26" width="380" height="44" as="geometry" />
        </mxCell>
        <mxCell id="bWU_UAJwaF4-bZPn0_Ai-19" value="" style="line;strokeWidth=1;fillColor=none;align=left;verticalAlign=middle;spacingTop=-1;spacingLeft=3;spacingRight=3;rotatable=0;labelPosition=right;points=[];portConstraint=eastwest;strokeColor=inherit;" vertex="1" parent="bWU_UAJwaF4-bZPn0_Ai-17">
          <mxGeometry y="70" width="380" height="8" as="geometry" />
        </mxCell>
        <mxCell id="bWU_UAJwaF4-bZPn0_Ai-20" value="&lt;div&gt;+ &lt;u&gt;new(String, String, String, LocalDate, Float, LocalDate, Integer)&lt;/u&gt;&lt;/div&gt;&lt;div&gt;- getHorasExtras(): Integer&lt;/div&gt;- sueldoBruto(): Float&lt;div&gt;- retenciones(): Float&lt;/div&gt;&lt;div&gt;- pagoHorasExtras(): Float&lt;/div&gt;&lt;div&gt;- retencionesObraSocial(): Float&lt;/div&gt;&lt;div&gt;- retencionesAportesJubilatorios(): Float&lt;/div&gt;&lt;div&gt;-&amp;nbsp;infoDesgloceConceptos(): String&lt;/div&gt;" style="text;strokeColor=none;fillColor=none;align=left;verticalAlign=top;spacingLeft=4;spacingRight=4;overflow=hidden;rotatable=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;whiteSpace=wrap;html=1;" vertex="1" parent="bWU_UAJwaF4-bZPn0_Ai-17">
          <mxGeometry y="78" width="380" height="132" as="geometry" />
        </mxCell>
        <mxCell id="bWU_UAJwaF4-bZPn0_Ai-24" value="ReciboDeHaberes" style="swimlane;fontStyle=1;align=center;verticalAlign=top;childLayout=stackLayout;horizontal=1;startSize=26;horizontalStack=0;resizeParent=1;resizeParentMax=0;resizeLast=0;collapsible=1;marginBottom=0;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="-30" y="460" width="330" height="180" as="geometry" />
        </mxCell>
        <mxCell id="bWU_UAJwaF4-bZPn0_Ai-25" value="- nombreEmpleado: String&amp;nbsp;&lt;div&gt;- direccion: String&lt;/div&gt;&lt;div&gt;- fechaEmision: LocalDate&amp;nbsp;&lt;/div&gt;&lt;div&gt;- sueldoBruto: Float&lt;/div&gt;&lt;div&gt;- sueldoNeto: Float&lt;/div&gt;&lt;div&gt;- desgloceConceptos: String&lt;/div&gt;" style="text;strokeColor=none;fillColor=none;align=left;verticalAlign=top;spacingLeft=4;spacingRight=4;overflow=hidden;rotatable=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;whiteSpace=wrap;html=1;" vertex="1" parent="bWU_UAJwaF4-bZPn0_Ai-24">
          <mxGeometry y="26" width="330" height="104" as="geometry" />
        </mxCell>
        <mxCell id="bWU_UAJwaF4-bZPn0_Ai-26" value="" style="line;strokeWidth=1;fillColor=none;align=left;verticalAlign=middle;spacingTop=-1;spacingLeft=3;spacingRight=3;rotatable=0;labelPosition=right;points=[];portConstraint=eastwest;strokeColor=inherit;" vertex="1" parent="bWU_UAJwaF4-bZPn0_Ai-24">
          <mxGeometry y="130" width="330" height="8" as="geometry" />
        </mxCell>
        <mxCell id="bWU_UAJwaF4-bZPn0_Ai-27" value="+ &lt;u&gt;new(String, String, LocalDate, Float, Float, String)&lt;/u&gt;" style="text;strokeColor=none;fillColor=none;align=left;verticalAlign=top;spacingLeft=4;spacingRight=4;overflow=hidden;rotatable=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;whiteSpace=wrap;html=1;" vertex="1" parent="bWU_UAJwaF4-bZPn0_Ai-24">
          <mxGeometry y="138" width="330" height="42" as="geometry" />
        </mxCell>
        <mxCell id="bWU_UAJwaF4-bZPn0_Ai-28" value="recibos" style="endArrow=block;endFill=1;html=1;edgeStyle=orthogonalEdgeStyle;align=left;verticalAlign=top;rounded=0;exitX=0.482;exitY=1.01;exitDx=0;exitDy=0;exitPerimeter=0;entryX=0.4;entryY=-0.004;entryDx=0;entryDy=0;entryPerimeter=0;" edge="1" parent="1" source="bWU_UAJwaF4-bZPn0_Ai-4" target="bWU_UAJwaF4-bZPn0_Ai-24">
          <mxGeometry x="-0.0815" y="-25" relative="1" as="geometry">
            <mxPoint x="680" y="420" as="sourcePoint" />
            <mxPoint x="840" y="420" as="targetPoint" />
            <mxPoint as="offset" />
          </mxGeometry>
        </mxCell>
        <mxCell id="bWU_UAJwaF4-bZPn0_Ai-29" value="1" style="edgeLabel;resizable=0;html=1;align=left;verticalAlign=bottom;" connectable="0" vertex="1" parent="bWU_UAJwaF4-bZPn0_Ai-28">
          <mxGeometry x="-1" relative="1" as="geometry">
            <mxPoint x="-19" y="19" as="offset" />
          </mxGeometry>
        </mxCell>
        <mxCell id="bWU_UAJwaF4-bZPn0_Ai-30" value="&lt;span style=&quot;color: rgb(0, 0, 0); font-family: Helvetica; font-size: 11px; font-style: normal; font-variant-ligatures: normal; font-variant-caps: normal; font-weight: 400; letter-spacing: normal; orphans: 2; text-align: left; text-indent: 0px; text-transform: none; widows: 2; word-spacing: 0px; -webkit-text-stroke-width: 0px; white-space: nowrap; background-color: rgb(255, 255, 255); text-decoration-thickness: initial; text-decoration-style: initial; text-decoration-color: initial; display: inline !important; float: none;&quot;&gt;*&lt;/span&gt;" style="text;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="70" y="430" width="40" height="40" as="geometry" />
        </mxCell>
        <mxCell id="bWU_UAJwaF4-bZPn0_Ai-33" value="" style="endArrow=block;endSize=16;endFill=0;html=1;rounded=0;" edge="1" parent="1" source="bWU_UAJwaF4-bZPn0_Ai-13" target="bWU_UAJwaF4-bZPn0_Ai-8">
          <mxGeometry x="-0.0022" width="160" relative="1" as="geometry">
            <mxPoint x="540" y="520" as="sourcePoint" />
            <mxPoint x="700" y="520" as="targetPoint" />
            <mxPoint as="offset" />
          </mxGeometry>
        </mxCell>
        <mxCell id="bWU_UAJwaF4-bZPn0_Ai-34" value="" style="endArrow=block;endSize=16;endFill=0;html=1;rounded=0;" edge="1" parent="1" source="bWU_UAJwaF4-bZPn0_Ai-17" target="bWU_UAJwaF4-bZPn0_Ai-8">
          <mxGeometry x="-0.0022" width="160" relative="1" as="geometry">
            <mxPoint x="773" y="540" as="sourcePoint" />
            <mxPoint x="895" y="359" as="targetPoint" />
            <mxPoint as="offset" />
          </mxGeometry>
        </mxCell>
      </root>
    </mxGraphModel>
  </diagram>
  <diagram id="Hjk06bJFGf4X8U3ZAHtm" name="Página-2">
    <mxGraphModel dx="2253" dy="751" grid="1" gridSize="10" guides="1" tooltips="1" connect="1" arrows="1" fold="1" page="1" pageScale="1" pageWidth="827" pageHeight="1169" math="0" shadow="0">
      <root>
        <mxCell id="0" />
        <mxCell id="1" parent="0" />
        <mxCell id="1fubEJdR3P5q25Fjkhi_-1" value="Empresa" style="swimlane;fontStyle=1;align=center;verticalAlign=top;childLayout=stackLayout;horizontal=1;startSize=26;horizontalStack=0;resizeParent=1;resizeParentMax=0;resizeLast=0;collapsible=1;marginBottom=0;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="80" y="70" width="370" height="170" as="geometry" />
        </mxCell>
        <mxCell id="1fubEJdR3P5q25Fjkhi_-2" value="- nombre: String&lt;div&gt;- cuil: Integer&lt;/div&gt;" style="text;strokeColor=none;fillColor=none;align=left;verticalAlign=top;spacingLeft=4;spacingRight=4;overflow=hidden;rotatable=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;whiteSpace=wrap;html=1;" vertex="1" parent="1fubEJdR3P5q25Fjkhi_-1">
          <mxGeometry y="26" width="370" height="34" as="geometry" />
        </mxCell>
        <mxCell id="1fubEJdR3P5q25Fjkhi_-3" value="" style="line;strokeWidth=1;fillColor=none;align=left;verticalAlign=middle;spacingTop=-1;spacingLeft=3;spacingRight=3;rotatable=0;labelPosition=right;points=[];portConstraint=eastwest;strokeColor=inherit;" vertex="1" parent="1fubEJdR3P5q25Fjkhi_-1">
          <mxGeometry y="60" width="370" height="8" as="geometry" />
        </mxCell>
        <mxCell id="1fubEJdR3P5q25Fjkhi_-4" value="+ &lt;u&gt;new(String, Integer, List&amp;lt;Empleado&amp;gt;, Set&amp;lt;ReciboDeHaberes&amp;gt;)&lt;/u&gt;&lt;div&gt;+ totalSueldosBrutos(): Float&lt;/div&gt;&lt;div&gt;+ totalRetenciones(): Float&lt;/div&gt;&lt;div&gt;+ totalSueldosNetos(): Float&amp;nbsp;&lt;/div&gt;&lt;div&gt;+ liquidarSueldos(): void&lt;/div&gt;" style="text;strokeColor=none;fillColor=none;align=left;verticalAlign=top;spacingLeft=4;spacingRight=4;overflow=hidden;rotatable=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;whiteSpace=wrap;html=1;" vertex="1" parent="1fubEJdR3P5q25Fjkhi_-1">
          <mxGeometry y="68" width="370" height="102" as="geometry" />
        </mxCell>
        <mxCell id="1fubEJdR3P5q25Fjkhi_-5" value="&lt;i&gt;Empleado&lt;/i&gt;" style="swimlane;fontStyle=1;align=center;verticalAlign=top;childLayout=stackLayout;horizontal=1;startSize=26;horizontalStack=0;resizeParent=1;resizeParentMax=0;resizeLast=0;collapsible=1;marginBottom=0;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="800" y="79" width="300" height="280" as="geometry" />
        </mxCell>
        <mxCell id="1fubEJdR3P5q25Fjkhi_-6" value="- nombre: String&lt;div&gt;- direccion: String&amp;nbsp;&lt;/div&gt;&lt;div&gt;- estadoCivil: String&lt;/div&gt;&lt;div&gt;- fechaDeNac: LocalDate&lt;/div&gt;&lt;div&gt;- sueldoBasico: Float&lt;/div&gt;" style="text;strokeColor=none;fillColor=none;align=left;verticalAlign=top;spacingLeft=4;spacingRight=4;overflow=hidden;rotatable=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;whiteSpace=wrap;html=1;" vertex="1" parent="1fubEJdR3P5q25Fjkhi_-5">
          <mxGeometry y="26" width="300" height="84" as="geometry" />
        </mxCell>
        <mxCell id="1fubEJdR3P5q25Fjkhi_-7" value="" style="line;strokeWidth=1;fillColor=none;align=left;verticalAlign=middle;spacingTop=-1;spacingLeft=3;spacingRight=3;rotatable=0;labelPosition=right;points=[];portConstraint=eastwest;strokeColor=inherit;" vertex="1" parent="1fubEJdR3P5q25Fjkhi_-5">
          <mxGeometry y="110" width="300" height="8" as="geometry" />
        </mxCell>
        <mxCell id="1fubEJdR3P5q25Fjkhi_-8" value="&lt;div&gt;+ &lt;u&gt;new(String, String, String, LocalDate, Float)&lt;/u&gt;&lt;/div&gt;&lt;div&gt;+ getNombre(): String&lt;/div&gt;&lt;div&gt;+ getDireccion(): String&lt;/div&gt;&lt;div&gt;+ getFechaNac(): LocalDate&lt;/div&gt;&lt;div&gt;+ getSueldoBasico(): Float&lt;/div&gt;+ edad(): Integer&lt;div&gt;&lt;i&gt;+ sueldoBruto(): Float&lt;/i&gt;&lt;/div&gt;&lt;div&gt;&lt;i&gt;+ retenciones(): Float&lt;/i&gt;&lt;/div&gt;&lt;div&gt;+ sueldoNeto(): Float&lt;/div&gt;&lt;div&gt;+ &lt;i&gt;infoDesgloceConceptos(): String&lt;/i&gt;&lt;/div&gt;" style="text;strokeColor=none;fillColor=none;align=left;verticalAlign=top;spacingLeft=4;spacingRight=4;overflow=hidden;rotatable=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;whiteSpace=wrap;html=1;" vertex="1" parent="1fubEJdR3P5q25Fjkhi_-5">
          <mxGeometry y="118" width="300" height="162" as="geometry" />
        </mxCell>
        <mxCell id="1fubEJdR3P5q25Fjkhi_-9" value="empleados" style="endArrow=block;endFill=1;html=1;edgeStyle=orthogonalEdgeStyle;align=left;verticalAlign=top;rounded=0;exitX=1;exitY=0.5;exitDx=0;exitDy=0;entryX=0;entryY=0.5;entryDx=0;entryDy=0;" edge="1" parent="1" source="1fubEJdR3P5q25Fjkhi_-4" target="1fubEJdR3P5q25Fjkhi_-6">
          <mxGeometry x="-0.4142" y="29" relative="1" as="geometry">
            <mxPoint x="340" y="400" as="sourcePoint" />
            <mxPoint x="500" y="400" as="targetPoint" />
            <mxPoint as="offset" />
          </mxGeometry>
        </mxCell>
        <mxCell id="1fubEJdR3P5q25Fjkhi_-10" value="1" style="edgeLabel;resizable=0;html=1;align=left;verticalAlign=bottom;" connectable="0" vertex="1" parent="1fubEJdR3P5q25Fjkhi_-9">
          <mxGeometry x="-1" relative="1" as="geometry" />
        </mxCell>
        <mxCell id="1fubEJdR3P5q25Fjkhi_-11" value="*" style="edgeLabel;resizable=0;html=1;align=left;verticalAlign=bottom;" connectable="0" vertex="1" parent="1">
          <mxGeometry x="580" y="190" as="geometry">
            <mxPoint x="194" y="-13" as="offset" />
          </mxGeometry>
        </mxCell>
        <mxCell id="1fubEJdR3P5q25Fjkhi_-14" value="EmpleadoTemporario" style="swimlane;fontStyle=1;align=center;verticalAlign=top;childLayout=stackLayout;horizontal=1;startSize=26;horizontalStack=0;resizeParent=1;resizeParentMax=0;resizeLast=0;collapsible=1;marginBottom=0;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="920" y="540" width="380" height="210" as="geometry" />
        </mxCell>
        <mxCell id="1fubEJdR3P5q25Fjkhi_-15" value="- fechaFinDesignacion: LocalDate&lt;div&gt;- cantHorasExtras: Integer&lt;/div&gt;" style="text;strokeColor=none;fillColor=none;align=left;verticalAlign=top;spacingLeft=4;spacingRight=4;overflow=hidden;rotatable=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;whiteSpace=wrap;html=1;" vertex="1" parent="1fubEJdR3P5q25Fjkhi_-14">
          <mxGeometry y="26" width="380" height="44" as="geometry" />
        </mxCell>
        <mxCell id="1fubEJdR3P5q25Fjkhi_-16" value="" style="line;strokeWidth=1;fillColor=none;align=left;verticalAlign=middle;spacingTop=-1;spacingLeft=3;spacingRight=3;rotatable=0;labelPosition=right;points=[];portConstraint=eastwest;strokeColor=inherit;" vertex="1" parent="1fubEJdR3P5q25Fjkhi_-14">
          <mxGeometry y="70" width="380" height="8" as="geometry" />
        </mxCell>
        <mxCell id="1fubEJdR3P5q25Fjkhi_-17" value="&lt;div&gt;+ &lt;u&gt;new(String, String, String, LocalDate, Float, LocalDate, Integer)&lt;/u&gt;&lt;/div&gt;&lt;div&gt;- getHorasExtras(): Integer&lt;/div&gt;- sueldoBruto(): Float&lt;div&gt;- retenciones(): Float&lt;/div&gt;&lt;div&gt;- pagoHorasExtras(): Float&lt;/div&gt;&lt;div&gt;- retencionesObraSocial(): Float&lt;/div&gt;&lt;div&gt;- retencionesAportesJubilatorios(): Float&lt;/div&gt;&lt;div&gt;-&amp;nbsp;infoDesgloceConceptos(): String&lt;/div&gt;" style="text;strokeColor=none;fillColor=none;align=left;verticalAlign=top;spacingLeft=4;spacingRight=4;overflow=hidden;rotatable=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;whiteSpace=wrap;html=1;" vertex="1" parent="1fubEJdR3P5q25Fjkhi_-14">
          <mxGeometry y="78" width="380" height="132" as="geometry" />
        </mxCell>
        <mxCell id="1fubEJdR3P5q25Fjkhi_-18" value="ReciboDeHaberes" style="swimlane;fontStyle=1;align=center;verticalAlign=top;childLayout=stackLayout;horizontal=1;startSize=26;horizontalStack=0;resizeParent=1;resizeParentMax=0;resizeLast=0;collapsible=1;marginBottom=0;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="-20" y="470" width="330" height="180" as="geometry" />
        </mxCell>
        <mxCell id="1fubEJdR3P5q25Fjkhi_-19" value="- nombreEmpleado: String&amp;nbsp;&lt;div&gt;- direccion: String&lt;/div&gt;&lt;div&gt;- fechaEmision: LocalDate&amp;nbsp;&lt;/div&gt;&lt;div&gt;- sueldoBruto: Float&lt;/div&gt;&lt;div&gt;- sueldoNeto: Float&lt;/div&gt;&lt;div&gt;- desgloceConceptos: String&lt;/div&gt;" style="text;strokeColor=none;fillColor=none;align=left;verticalAlign=top;spacingLeft=4;spacingRight=4;overflow=hidden;rotatable=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;whiteSpace=wrap;html=1;" vertex="1" parent="1fubEJdR3P5q25Fjkhi_-18">
          <mxGeometry y="26" width="330" height="104" as="geometry" />
        </mxCell>
        <mxCell id="1fubEJdR3P5q25Fjkhi_-20" value="" style="line;strokeWidth=1;fillColor=none;align=left;verticalAlign=middle;spacingTop=-1;spacingLeft=3;spacingRight=3;rotatable=0;labelPosition=right;points=[];portConstraint=eastwest;strokeColor=inherit;" vertex="1" parent="1fubEJdR3P5q25Fjkhi_-18">
          <mxGeometry y="130" width="330" height="8" as="geometry" />
        </mxCell>
        <mxCell id="1fubEJdR3P5q25Fjkhi_-21" value="+ &lt;u&gt;new(String, String, LocalDate, Float, Float, String)&lt;/u&gt;" style="text;strokeColor=none;fillColor=none;align=left;verticalAlign=top;spacingLeft=4;spacingRight=4;overflow=hidden;rotatable=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;whiteSpace=wrap;html=1;" vertex="1" parent="1fubEJdR3P5q25Fjkhi_-18">
          <mxGeometry y="138" width="330" height="42" as="geometry" />
        </mxCell>
        <mxCell id="1fubEJdR3P5q25Fjkhi_-22" value="recibos" style="endArrow=block;endFill=1;html=1;edgeStyle=orthogonalEdgeStyle;align=left;verticalAlign=top;rounded=0;exitX=0.482;exitY=1.01;exitDx=0;exitDy=0;exitPerimeter=0;entryX=0.4;entryY=-0.004;entryDx=0;entryDy=0;entryPerimeter=0;" edge="1" parent="1" source="1fubEJdR3P5q25Fjkhi_-4" target="1fubEJdR3P5q25Fjkhi_-18">
          <mxGeometry x="-0.0815" y="-25" relative="1" as="geometry">
            <mxPoint x="690" y="430" as="sourcePoint" />
            <mxPoint x="850" y="430" as="targetPoint" />
            <mxPoint as="offset" />
          </mxGeometry>
        </mxCell>
        <mxCell id="1fubEJdR3P5q25Fjkhi_-23" value="1" style="edgeLabel;resizable=0;html=1;align=left;verticalAlign=bottom;" connectable="0" vertex="1" parent="1fubEJdR3P5q25Fjkhi_-22">
          <mxGeometry x="-1" relative="1" as="geometry">
            <mxPoint x="-19" y="19" as="offset" />
          </mxGeometry>
        </mxCell>
        <mxCell id="1fubEJdR3P5q25Fjkhi_-24" value="&lt;span style=&quot;color: rgb(0, 0, 0); font-family: Helvetica; font-size: 11px; font-style: normal; font-variant-ligatures: normal; font-variant-caps: normal; font-weight: 400; letter-spacing: normal; orphans: 2; text-align: left; text-indent: 0px; text-transform: none; widows: 2; word-spacing: 0px; -webkit-text-stroke-width: 0px; white-space: nowrap; background-color: rgb(255, 255, 255); text-decoration-thickness: initial; text-decoration-style: initial; text-decoration-color: initial; display: inline !important; float: none;&quot;&gt;*&lt;/span&gt;" style="text;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="80" y="440" width="40" height="40" as="geometry" />
        </mxCell>
        <mxCell id="1fubEJdR3P5q25Fjkhi_-25" value="" style="endArrow=block;endSize=16;endFill=0;html=1;rounded=0;" edge="1" parent="1" target="1fubEJdR3P5q25Fjkhi_-8" source="tUgyoDJAsifHRwG3QqX5-1">
          <mxGeometry x="-0.0022" width="160" relative="1" as="geometry">
            <mxPoint x="773" y="540" as="sourcePoint" />
            <mxPoint x="710" y="530" as="targetPoint" />
            <mxPoint as="offset" />
          </mxGeometry>
        </mxCell>
        <mxCell id="1fubEJdR3P5q25Fjkhi_-26" value="" style="endArrow=block;endSize=16;endFill=0;html=1;rounded=0;" edge="1" parent="1" source="1fubEJdR3P5q25Fjkhi_-14" target="1fubEJdR3P5q25Fjkhi_-8">
          <mxGeometry x="-0.0022" width="160" relative="1" as="geometry">
            <mxPoint x="783" y="550" as="sourcePoint" />
            <mxPoint x="905" y="369" as="targetPoint" />
            <mxPoint as="offset" />
          </mxGeometry>
        </mxCell>
        <mxCell id="tUgyoDJAsifHRwG3QqX5-1" value="EmpleadoPermanente" style="swimlane;fontStyle=1;align=center;verticalAlign=top;childLayout=stackLayout;horizontal=1;startSize=26;horizontalStack=0;resizeParent=1;resizeParentMax=0;resizeLast=0;collapsible=1;marginBottom=0;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="500" y="540" width="350" height="260" as="geometry" />
        </mxCell>
        <mxCell id="tUgyoDJAsifHRwG3QqX5-2" value="- cantHijos: Integer&lt;div&gt;- antiguedad: Integer&lt;/div&gt;" style="text;strokeColor=none;fillColor=none;align=left;verticalAlign=top;spacingLeft=4;spacingRight=4;overflow=hidden;rotatable=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;whiteSpace=wrap;html=1;" vertex="1" parent="tUgyoDJAsifHRwG3QqX5-1">
          <mxGeometry y="26" width="350" height="44" as="geometry" />
        </mxCell>
        <mxCell id="tUgyoDJAsifHRwG3QqX5-3" value="" style="line;strokeWidth=1;fillColor=none;align=left;verticalAlign=middle;spacingTop=-1;spacingLeft=3;spacingRight=3;rotatable=0;labelPosition=right;points=[];portConstraint=eastwest;strokeColor=inherit;" vertex="1" parent="tUgyoDJAsifHRwG3QqX5-1">
          <mxGeometry y="70" width="350" height="8" as="geometry" />
        </mxCell>
        <mxCell id="tUgyoDJAsifHRwG3QqX5-4" value="&lt;div&gt;+ &lt;u&gt;new(String, String, String, LocalDate, Float, Integer, Integer)&lt;/u&gt;&lt;/div&gt;&lt;div&gt;&lt;div&gt;- getCantHijos(): Integer&lt;/div&gt;&lt;div&gt;- getAntiguedad(): Integer&lt;/div&gt;&lt;/div&gt;- sueldoBruto(): Float&lt;div&gt;- retenciones(): Float&lt;/div&gt;&lt;div&gt;- salarioFamiliar(): Float&amp;nbsp;&lt;/div&gt;&lt;div&gt;- pagoAsignacionPorHijo(): Float&amp;nbsp;&lt;/div&gt;&lt;div&gt;- pagoAsignacionPorConyuge(): Float&lt;/div&gt;&lt;div&gt;- pagoAntiguedad(): Float&lt;/div&gt;&lt;div&gt;- retencionesObraSocial(): Float&lt;/div&gt;&lt;div&gt;- retencionesAportesJubilatorios(): Float&amp;nbsp;&amp;nbsp;&lt;/div&gt;&lt;div&gt;-&amp;nbsp;infoDesgloceConceptos(): String&lt;/div&gt;" style="text;strokeColor=none;fillColor=none;align=left;verticalAlign=top;spacingLeft=4;spacingRight=4;overflow=hidden;rotatable=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;whiteSpace=wrap;html=1;" vertex="1" parent="tUgyoDJAsifHRwG3QqX5-1">
          <mxGeometry y="78" width="350" height="182" as="geometry" />
        </mxCell>
        <mxCell id="LCLo46TiwDn-tqvHDEYn-1" value="EmpleadoContratado" style="swimlane;fontStyle=1;align=center;verticalAlign=top;childLayout=stackLayout;horizontal=1;startSize=26;horizontalStack=0;resizeParent=1;resizeParentMax=0;resizeLast=0;collapsible=1;marginBottom=0;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="1350" y="350" width="380" height="160" as="geometry" />
        </mxCell>
        <mxCell id="LCLo46TiwDn-tqvHDEYn-2" value="- numeroDeContrato: Integer&lt;div&gt;- medioDePago: String&lt;/div&gt;" style="text;strokeColor=none;fillColor=none;align=left;verticalAlign=top;spacingLeft=4;spacingRight=4;overflow=hidden;rotatable=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;whiteSpace=wrap;html=1;" vertex="1" parent="LCLo46TiwDn-tqvHDEYn-1">
          <mxGeometry y="26" width="380" height="44" as="geometry" />
        </mxCell>
        <mxCell id="LCLo46TiwDn-tqvHDEYn-3" value="" style="line;strokeWidth=1;fillColor=none;align=left;verticalAlign=middle;spacingTop=-1;spacingLeft=3;spacingRight=3;rotatable=0;labelPosition=right;points=[];portConstraint=eastwest;strokeColor=inherit;" vertex="1" parent="LCLo46TiwDn-tqvHDEYn-1">
          <mxGeometry y="70" width="380" height="8" as="geometry" />
        </mxCell>
        <mxCell id="LCLo46TiwDn-tqvHDEYn-4" value="&lt;div&gt;+ &lt;u&gt;new(String, String, String, LocalDate, Float, Integer, String)&lt;/u&gt;&lt;/div&gt;- sueldoBruto(): Float&lt;div&gt;- retenciones(): Float&lt;/div&gt;&lt;div&gt;- gastosContractuales(): Float&lt;/div&gt;&lt;div&gt;-&amp;nbsp;infoDesgloceConceptos(): String&lt;/div&gt;" style="text;strokeColor=none;fillColor=none;align=left;verticalAlign=top;spacingLeft=4;spacingRight=4;overflow=hidden;rotatable=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;whiteSpace=wrap;html=1;" vertex="1" parent="LCLo46TiwDn-tqvHDEYn-1">
          <mxGeometry y="78" width="380" height="82" as="geometry" />
        </mxCell>
        <mxCell id="Y_gvpZaYzOKEoWeEI1hz-1" value="" style="endArrow=block;endSize=16;endFill=0;html=1;rounded=0;" edge="1" parent="1" source="LCLo46TiwDn-tqvHDEYn-1" target="1fubEJdR3P5q25Fjkhi_-8">
          <mxGeometry x="-0.0022" width="160" relative="1" as="geometry">
            <mxPoint x="1319" y="441" as="sourcePoint" />
            <mxPoint x="1240" y="260" as="targetPoint" />
            <mxPoint as="offset" />
          </mxGeometry>
        </mxCell>
      </root>
    </mxGraphModel>
  </diagram>
</mxfile>
UML Ejercicio 2 TP2.drawio…]()
