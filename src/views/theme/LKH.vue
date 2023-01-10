<template>
  <CRow>
    <CCol>
      <h1>PROGRESS HARIAN FUNGSIONAL</h1>
      <CCard class="mb-4"> </CCard>
      <CCard class="mb-4">
        <CCardHeader><b> Informasi Identitas Pegawai </b></CCardHeader>
        <CCardBody>
          <div class="bd-example">
            <dl class="row">
              <dt class="col-sm-3">Nama Pegawai :</dt>
              <dd class="col-sm-9">
                <p>Budianto</p>
              </dd>

              <dt class="col-sm-3">NIP :</dt>
              <dd class="col-sm-9">
                <p>0123456789</p>
              </dd>

              <dt class="col-sm-3">Unit Kerja :</dt>
              <dd class="col-sm-9">
                <p>Sub Keuangan</p>
              </dd>

              <dt class="col-sm-3">Satuan Kerja :</dt>
              <dd class="col-sm-9">
                <dl class="row">
                  <dd class="col-sm-8">
                    <p>
                      Pusat Teknologi Informasi dan Pangkalan Data UIN Ar-Raniry
                    </p>
                  </dd>
                </dl>
              </dd>
            </dl>
          </div>
        </CCardBody>
      </CCard>
      <CCard class="mb-4">
        <CCardHeader><b> Data Pekerjaan Harian </b></CCardHeader>
        <CButton color="primary" variant="outline">Tambah Pekerjaan</CButton>
      </CCard>
      <CCard>
        <CCardBody>
          <CForm>
            <b>
              <CFormInput type="text" id="formControlTanggal" label="Tanggal" />
            </b>
          </CForm>

          <CForm class="mt-2 mb-2">
            <b>BAB Pekerjaan</b>
            <CFormSelect
              :options="[
                'Pilih BAB',
                {
                  label:
                    'BAB I : TATA KELOLA DAN TATA LAKSANA TEKNOLOGI INFORMASI',
                  value: '1',
                },
                {
                  label: 'BAB II : INFRASTRUKTUR TEKNOLOGI INFORMASI',
                  value: '2',
                },
                {
                  label: 'BAB III : SISTEM INFORMASI DAN MULTIMEDIA',
                  value: '3',
                },
                {
                  label: 'BAB IV : PENGEMBANGAN PROFESI',
                  value: '4',
                },
                {
                  label: 'BAB V : PENUNJANG KEGIATAN PRANATA KOMPUTER',
                  value: '5',
                },
              ]"
            >
            </CFormSelect>
          </CForm>

          <CForm class="mt-2 mb-2">
            <b>Sub-BAB</b>
            <CFormSelect
              :options="[
                'Pilih Sub-BAB',
                {
                  label:
                    'BAB I : TATA KELOLA DAN TATA LAKSANA TEKNOLOGI INFORMASI',
                  value: '1',
                },
                {
                  label: 'BAB II : INFRASTRUKTUR TEKNOLOGI INFORMASI',
                  value: '2',
                },
                {
                  label: 'BAB III : SISTEM INFORMASI DAN MULTIMEDIA',
                  value: '3',
                },
                {
                  label: 'BAB IV : PENGEMBANGAN PROFESI',
                  value: '4',
                },
                {
                  label: 'BAB V : PENUNJANG KEGIATAN PRANATA KOMPUTER',
                  value: '5',
                },
              ]"
            >
            </CFormSelect>
          </CForm>

          <CForm class="mt-2 mb-2">
            <b>Butir Pekerjaan</b>
            <CFormSelect
              :options="[
                'Pilih Butir pekerjaan',
                {
                  label:
                    'BAB I : TATA KELOLA DAN TATA LAKSANA TEKNOLOGI INFORMASI',
                  value: '1',
                },
                {
                  label: 'BAB II : INFRASTRUKTUR TEKNOLOGI INFORMASI',
                  value: '2',
                },
                {
                  label: 'BAB III : SISTEM INFORMASI DAN MULTIMEDIA',
                  value: '3',
                },
                {
                  label: 'BAB IV : PENGEMBANGAN PROFESI',
                  value: '4',
                },
                {
                  label: 'BAB V : PENUNJANG KEGIATAN PRANATA KOMPUTER',
                  value: '5',
                },
              ]"
            >
            </CFormSelect>
          </CForm>

          <CForm class="mt-2 mb-2">
            <b>
              <CFormInput
                type="text"
                id="formControlDeskripsi"
                label="Deskripsi Pekerjaan"
              />
            </b>
          </CForm>

          <CForm class="mt-2 mb-2">
            <div class="mb-3">
              <b><CFormLabel for="formFile">Upload Bukti</CFormLabel></b>
              <CFormInput id="formFile" type="file" />
            </div>
          </CForm>

          <CForm class="mt-2 mb-2">
            <b>
              <CFormInput type="text" id="formControlLink" label="Bukti Link" />
            </b>
          </CForm>
          <CForm class="mt-2 mb-2">
            <b>Periode Progress</b>
            <CFormSelect
              :options="[
                'Pilih Periode',
                {
                  label: 'Ganjil 2023',
                  value: '1',
                },
                {
                  label: 'Genap 2023',
                  value: '2',
                },
              ]"
            >
            </CFormSelect>
          </CForm>
          <br />

          <CForm>
            <CButton color="dark">Submit</CButton>
          </CForm>
        </CCardBody>
      </CCard>
    </CCol>
  </CRow>
</template>

<script></script>
