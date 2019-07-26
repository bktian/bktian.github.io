<title>
	OA打印模板
</title>
<meta charset="utf-8" />
<style>
html * {
	font-size: 12px;
	line-height: 24px;
}
table {
	border-collapse: collapse
}
td {
	border: 1px solid black;
	line-height: 35px;
}
textarea {
       width:100%;
       height:200px;
}
.align-center {
	text-align: center;
}
.content-padding {
	padding-left: 5px;
}
.flow-option {
	height: 50px;
	vertical-align: top;
}
.flow-option-content {
	height: 30px;
	vertical-align: top;
	border: 0px;
}
.flow-option-sign {
	padding-right: 5px;
	border: 0px;
	text-align: right;
}
</style>
<div id="page1" autobreaktable="*" class="paperWidth" style="padding:0 20px;width:700px;">
	<table style="width:100%;" class="ke-zeroborder" border="0" cellpadding="0" cellspacing="0">
		<tbody>
			<tr>
				<td colspan="6">
					<h1 style="font-size:1.5em;text-align:center;position:relative;width:500px;margin:0 auto;line-height:40px;">
						资产报废处置单
					</h1>
				</td>
			</tr>
			<tr>
				<td class="align-center" width="15%">
					单据编号
				</td>
				<td colspan="2" width="30%">
					formcontrol#bills_no#
				</td>
				<td class="align-center" width="15%">
					申请日期
				</td>
				<td colspan="2">
					formcontrol#created#
				</td>
			</tr>
			<tr>
				<td class="align-center" width="15%">
					申请人
				</td>
				<td colspan="2" width="30%">
					formcontrol#creator_name#
				</td>
				<td class="align-center" width="15%">
					申请部门
				</td>
				<td colspan="2">
					formcontrol#organizationInfo#
				</td>
			</tr>
			<tr>
				<td class="align-center" width="15%">
					物资类型
				</td>
				<td colspan="5">
					formcontrol#Type#
				</td>
			</tr>
			<tr>
				<td colspan="5">
					formcontrol#mx#
				</td>
			</tr>
			<tr>
				<td class="align-center" width="15%">
					报废原因
				</td>
				<td colspan="5">
					formcontrol#Reason#
				</td>
			</tr>
			<tr keeptogether="true">
				<td keeptogether2="true" class=" align-center" style="padding-bottom:none;" width="20%">
					IT部负责人（电子设备类）：
				</td>
				<td keeptogether2="true" class=" flow-option content-padding" colspan="5" width="80%">
					<table style="width:100%;" class="ke-zeroborder" border="0">
						<tbody>
							<tr>
								<td class="flow-option-content">
									$!IT.opinion&nbsp;
								</td>
							</tr>
							<tr>
								<td class="flow-option-sign">
									$!IT.allocateUser
							&nbsp;&nbsp;&nbsp;&nbsp; $!dateTool.format('yyyy-MM-dd HH:mm:ss
							',$!IT.allocateDate)
								</td>
							</tr>
						</tbody>
					</table>
				</td>
			</tr>
			<tr keeptogether="true">
				<td keeptogether2="true" class=" align-center" style="padding-bottom:none;" width="20%">
					测试部：林子荣
				</td>
				<td keeptogether2="true" class=" flow-option content-padding" colspan="5" width="80%">
					<table style="width:100%;" class="ke-zeroborder" border="0">
						<tbody>
							<tr>
								<td class="flow-option-content">
									$!cs.opinion&nbsp;
								</td>
							</tr>
							<tr>
								<td class="flow-option-sign">
									$!cs.allocateUser
							&nbsp;&nbsp;&nbsp;&nbsp; $!dateTool.format('yyyy-MM-dd HH:mm:ss
							',$!cs.allocateDate)
								</td>
							</tr>
						</tbody>
					</table>
				</td>
			</tr>
			<tr keeptogether="true">
				<td keeptogether2="true" class=" align-center" style="padding-bottom:none;" width="20%">
					固定资产管理员审核：邓浪
				</td>
				<td keeptogether2="true" class=" flow-option content-padding" colspan="5" width="80%">
					<table style="width:100%;" class="ke-zeroborder" border="0">
						<tbody>
							<tr>
								<td class="flow-option-content">
									$!GDZCGL.opinion&nbsp;
								</td>
							</tr>
							<tr>
								<td class="flow-option-sign">
									$!GDZCGL.allocateUser
							&nbsp;&nbsp;&nbsp;&nbsp; $!dateTool.format('yyyy-MM-dd HH:mm:ss
							',$!GDZCGL.allocateDate)
								</td>
							</tr>
						</tbody>
					</table>
				</td>
			</tr>
			<tr keeptogether="true">
				<td keeptogether2="true" class=" align-center" style="padding-bottom:none;" width="20%">
					财务部负责人意见<span lang="EN-US">:</span>赵敏
				</td>
				<td keeptogether2="true" class=" flow-option content-padding" colspan="5" width="80%">
					<table style="width:100%;" class="ke-zeroborder" border="0">
						<tbody>
							<tr>
								<td class="flow-option-content">
									$!CWB.opinion&nbsp;
								</td>
							</tr>
							<tr>
								<td class="flow-option-sign">
									$!CWB.allocateUser
							&nbsp;&nbsp;&nbsp;&nbsp; $!dateTool.format('yyyy-MM-dd HH:mm:ss
							',$!CWB.allocateDate)
								</td>
							</tr>
						</tbody>
					</table>
				</td>
			</tr>
			<tr keeptogether="true">
				<td keeptogether2="true" class=" align-center" style="padding-bottom:none;" width="20%">
					分管副总裁审批：
				</td>
				<td keeptogether2="true" class=" flow-option content-padding" colspan="5" width="80%">
					<table style="width:100%;" class="ke-zeroborder" border="0">
						<tbody>
							<tr>
								<td class="flow-option-content">
									$!FGLD.opinion&nbsp;
								</td>
							</tr>
							<tr>
								<td class="flow-option-sign">
									$!FGLD.allocateUser
							&nbsp;&nbsp;&nbsp;&nbsp; $!dateTool.format('yyyy-MM-dd HH:mm:ss
							',$!FGLD.allocateDate)
								</td>
							</tr>
						</tbody>
					</table>
				</td>
			</tr>
			<tr keeptogether="true">
				<td keeptogether2="true" class=" align-center" style="padding-bottom:none;" width="20%">
					总裁审批：：
				</td>
				<td keeptogether2="true" class=" flow-option content-padding" colspan="5" width="80%">
					<table style="width:100%;" class="ke-zeroborder" border="0">
						<tbody>
							<tr>
								<td class="flow-option-content">
									$!ZC.opinion&nbsp;
								</td>
							</tr>
							<tr>
								<td class="flow-option-sign">
									$!ZC.allocateUser
							&nbsp;&nbsp;&nbsp;&nbsp; $!dateTool.format('yyyy-MM-dd HH:mm:ss
							',$!ZC.allocateDate)
								</td>
							</tr>
						</tbody>
					</table>
				</td>
			</tr>
		</tbody>
	</table>
</div>
